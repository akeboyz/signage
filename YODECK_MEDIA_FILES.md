# Media Files for Yodeck Upload

## Instructions
Upload these files to Yodeck media library and place them in the `/opt/yodeck/medias/` directory structure.

## Required Video Files
Upload these MP4 files to Yodeck:

### Category Videos (Essential)
- `daily.mp4` - Daily services category video
- `deal.mp4` - Deals category video
- `delivery.mp4` - Delivery services category video
- `dining.mp4` - Dining category video
- `juristic.mp4` - Juristic services category video
- `ondemand.mp4` - On-demand services category video

### Project Videos
- `project.mp4` - Main project overview video (top banner in menu)
- `main_menu.mp4` - Alternative main menu video
- `juristic_update.mp4` - Juristic updates video

### Branding Files
- `prj001_logo.png` - Project 1 logo
- `prj002_logo.png` - Project 2 logo
- `prj003_logo.png` - **Mahogany** project logo (main)
- `prj004_logo.png` - Project 4 logo
- `cover.png` - General cover image
- `pm001_logo.png` - Property Manager 1 logo
- `pm002_logo.png` - Property Manager 2 logo
- `pm003_logo.png` - Property Manager 3 logo

### Essential Images
- `placeholder.jpg` - Default fallback image (already included in deployment)

### Category Service Images (Referenced in JSON)
#### Daily Services:
- `daily-shuttle.jpg`
- `daily-gym.jpg`
- `daily-garbage.jpg`
- `daily-security.jpg`

#### Delivery Services:
- `delivery-foodpanda.jpg`
- `delivery-grab.jpg`
- `delivery-lineman.jpg`
- `delivery-shopee.jpg`

#### Deal Images:
- `deal-happyhour.jpg`
- `deal-buy1get1.jpg`
- `deal-bbq.jpg`
- `deal-pasta.jpg`

#### On-Demand Services:
- `ondemand-cleaning.jpg`
- `ondemand-grocery.jpg`
- `ondemand-laundry.jpg`
- `ondemand-petcare.jpg`

#### Juristic Services:
- `juristic-payment.jpg`
- `juristic-meeting.jpg`
- `juristic-maintenance.jpg`
- `juristic-rules.jpg`

### Shop/Unit Media (Optional - if available)
- `unit001-01.mp4`
- `shop001-01.mp4`
- `shop002-01.mp4`
- `rest001-01.mp4`

## Yodeck Setup Steps
1. Upload all files to Yodeck Media Library
2. Ensure files are placed in `/opt/yodeck/medias/` directory
3. Test the signage URLs to verify media loads correctly
4. **Important**: All shop/restaurant item images are hosted on Unsplash (external URLs) and don't need uploading

## Deployment Size Savings
- **Before**: ~50MB+ with videos
- **After**: ~1MB (HTML, CSS, JS, JSON only)
- **Result**: Faster deployment, better performance, reduced bandwidth usage