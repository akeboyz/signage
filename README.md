# Mahogany Sukhumvit 24 - Digital Signage System

This folder contains the optimized deployment package for Mahogany project (prj003) digital signage system.

## ✅ Optimized for Yodeck Integration
- **Media files stored locally on Yodeck** (faster loading, no internet dependency)
- **Code deployed to Netlify** (easy updates, reliable hosting)
- **Minimal deployment size** (~1MB vs ~50MB+)

## Files Included:
- `signage.html` - Main signage interface
- `menu.html` - Menu navigation page
- `category.html` - Category browsing page
- `shop-signage.html` - Shop details page
- `rest-signage.html` - Restaurant details page
- `unit-signage.html` - Property unit details page
- `index.html` - Auto-redirects to signage.html with project_id=prj003
- `data/` - All JSON data files with shop, restaurant, and project information
- `medias/` - Only placeholder.jpg (videos removed for optimization)
- `YODECK_MEDIA_FILES.md` - **IMPORTANT**: List of files to upload to Yodeck

## 🚀 Deployment Steps:

### Step 1: Upload Media to Yodeck
1. Review `YODECK_MEDIA_FILES.md` for complete list
2. Upload all video and image files to Yodeck Media Library
3. Ensure files are placed in `/opt/yodeck/medias/` directory structure

### Step 2: Deploy Code to Netlify
1. Upload this entire folder to Netlify (drag & drop)
2. Get your Netlify URL (e.g., `https://mahogany-signage.netlify.app`)
3. Use this URL in Yodeck display settings

### Step 3: Configure Yodeck
1. Create new layout in Yodeck
2. Add web widget pointing to your Netlify URL
3. Ensure media files are accessible at `/opt/yodeck/medias/`

## 🔗 Entry Points:
- **Main Signage**: `https://your-netlify-url/signage.html?project_id=prj003`
- **Auto-Redirect**: `https://your-netlify-url/` (index.html auto-redirects)

## 📊 Project Details:
- **Project ID**: prj003
- **Project Name**: Mahogany Sukhumvit 24
- **Categories**: Daily, Dining, Delivery, On-Demand, Deal
- **Shops**: 12 active shops with complete item catalogs
- **Restaurants**: 3 active restaurants with full menus
- **External Images**: All item/menu images hosted on Unsplash (no upload needed)