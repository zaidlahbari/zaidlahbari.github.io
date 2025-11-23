# 📷 Image Assets Guide

This folder contains all the images for the Zaid Lahbari Taxi & Transport website.

## 📁 Folder Structure

```
assets/
└── images/
    ├── hero/           # Hero section background images
    ├── destinations/   # Destination excursion photos
    └── attractions/    # Marrakech tourist sites photos
```

## 🖼️ Recommended Images to Add

Currently, the website uses placeholder images from Unsplash. For the best professional look, replace them with actual photos.

### Hero Section (`hero/`)
- **hero-marrakech.jpg** (1920x1080px)
  - Your taxi in front of iconic Marrakech location
  - Koutoubia Mosque backdrop
  - Sunset in Marrakech with your vehicle

### Destinations (`destinations/`)
Each image should be 1200x800px minimum:

1. **ourika-valley.jpg** - Ourika waterfalls and valley views
2. **essaouira-beach.jpg** - Coastal town, blue boats, medina walls
3. **ouzoud-waterfalls.jpg** - Cascades with rainbow/macaques
4. **ouarzazate-kasbah.jpg** - Ait Benhaddou or Taourirt Kasbah
5. **casablanca-mosque.jpg** - Hassan II Mosque
6. **agadir-beach.jpg** - Beach and modern waterfront
7. **agafay-desert.jpg** - Rocky desert landscape, sunset

### Marrakech Attractions (`attractions/`)
Each image should be 800x600px minimum:

1. **majorelle-gardens.jpg** - Blue villa and exotic plants
2. **bahia-palace.jpg** - Colorful tiles and architecture
3. **badiaa-palace.jpg** - Ruins and storks
4. **saadian-tombs.jpg** - Ornate tomb interior
5. **koutoubia-mosque.jpg** - Minaret and gardens
6. **menara-gardens.jpg** - Pavilion and olive groves
7. **jemaa-el-fnaa.jpg** - Square with market stalls

## 📸 Photo Sources

### Option 1: Use Your Own Photos ⭐ (Recommended)
- Most authentic and professional
- Shows your actual vehicles and services
- Builds trust with potential clients

### Option 2: Free Stock Photos
- **Unsplash** (https://unsplash.com/) - High quality, free
- **Pexels** (https://pexels.com/) - Large selection
- **Pixabay** (https://pixabay.com/) - Free for commercial use

Search terms:
- "Marrakech Morocco"
- "Morocco taxi yellow"
- "Moroccan desert"
- "Atlas Mountains"
- "Moroccan architecture"

### Option 3: Hire Local Photographer
- Professional shots of you with your vehicle
- Action shots during tours
- Customer experiences (with permission)

## 🎨 Image Requirements

### Technical Specs:
- **Format:** JPG (for photos), PNG (for logos/graphics)
- **Resolution:** Minimum 1920px wide for hero images
- **File Size:** Optimize to <500KB per image for fast loading
- **Color:** Vibrant colors that complement yellow/black theme

### Composition Tips:
- Show your vehicle in good lighting
- Include recognizable Moroccan landmarks
- Capture authentic tourist experiences
- Avoid overly touristy/stock photo look

## 🔧 Image Optimization

Before uploading, optimize images using:

### Online Tools:
- **TinyPNG** (https://tinypng.com/) - Compress without quality loss
- **Squoosh** (https://squoosh.app/) - Advanced compression
- **Compressor.io** (https://compressor.io/) - Fast batch processing

### Desktop Apps:
- **Adobe Photoshop** - Save for Web
- **GIMP** (Free) - Export with compression
- **XnConvert** (Free) - Batch processing

## 📝 Image Naming Convention

Use clear, descriptive names:
- ✅ `ourika-valley-waterfalls.jpg`
- ✅ `taxi-marrakech-koutoubia.jpg`
- ✅ `essaouira-beach-sunset.jpg`
- ❌ `IMG_1234.jpg`
- ❌ `photo1.jpg`

## 🔄 Replacing Placeholder Images

After adding your images to the folders, update the HTML file:

1. Open `index.html`
2. Find image sources (search for `unsplash.com`)
3. Replace with your local paths:

```html
<!-- BEFORE -->
<img src="https://images.unsplash.com/photo-xxxxx" alt="...">

<!-- AFTER -->
<img src="assets/images/destinations/ourika-valley.jpg" alt="Ourika Valley">
```

## 💡 Additional Image Ideas

### For Future Enhancements:
- **Team photos** - You with your vehicle
- **Customer testimonials** - Happy clients (with permission)
- **Vehicle interior** - Show comfort and cleanliness
- **Trip gallery** - Create a photo gallery section
- **Behind the scenes** - Preparing for tours

## ⚠️ Legal Considerations

- **Copyright:** Only use images you own or have rights to
- **Model releases:** Get permission if identifiable people are shown
- **Property releases:** Some landmarks require permission for commercial use
- **Attribution:** Credit photographers if required by license

## 📱 Responsive Images

The current website uses:
- **Desktop:** Full resolution images
- **Mobile:** Automatically scaled with CSS
- **Lazy loading:** Images load as you scroll for faster page load

No action needed - already optimized in the code!

---

**Need Help?** Contact a web developer or photographer to get professional images for your website.