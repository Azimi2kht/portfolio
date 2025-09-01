# 📸 Image Setup Guide

This guide will help you add your personal images to the portfolio.

## 🖼️ Required Images

### 1. Profile Photo
- **File**: `images/profile/profile.jpg`
- **Size**: 400x400 pixels (square)
- **Format**: JPG or PNG
- **Content**: Professional headshot

### 2. Project Images
- **LLM Project**: `images/projects/llm-project.jpg`
- **Medical Segmentation**: `images/projects/medical-segmentation.jpg`
- **Smart Home**: `images/projects/smart-home.jpg`
- **Size**: 600x400 pixels (3:2 ratio)
- **Format**: JPG or PNG

## 🛠️ How to Add Images

### Option 1: Using Your Own Images
1. **Prepare your images**:
   - Resize profile photo to 400x400px
   - Resize project images to 600x400px
   - Optimize file sizes (keep under 500KB each)

2. **Add to portfolio**:
   ```bash
   # Copy your profile photo
   cp /path/to/your/photo.jpg images/profile/profile.jpg
   
   # Copy your project images
   cp /path/to/llm-screenshot.jpg images/projects/llm-project.jpg
   cp /path/to/medical-screenshot.jpg images/projects/medical-segmentation.jpg
   cp /path/to/smart-home-screenshot.jpg images/projects/smart-home.jpg
   ```

### Option 2: Using Online Tools
1. **For profile photo**:
   - Use tools like Canva, Remove.bg, or Photopea
   - Create a professional headshot with clean background
   - Download as 400x400px JPG

2. **For project images**:
   - Take screenshots of your projects
   - Create mockups using tools like Figma or Canva
   - Use AI image generators for concept visuals

### Option 3: Using AI-Generated Images
1. **Profile photo**: Use AI tools like Midjourney, DALL-E, or Stable Diffusion
2. **Project images**: Generate concept images related to your projects

## 🎨 Image Ideas for Projects

### LLM Enhancement Project
- Knowledge graph visualization
- Architecture diagram
- Before/after comparison of model performance
- Screenshot of the system interface

### Medical Image Segmentation
- Original ultrasound image
- Segmented result overlay
- U-Net architecture diagram
- Performance metrics visualization

### Smart Home System
- Raspberry Pi setup
- ThingsBoard dashboard screenshot
- YOLO detection results
- System architecture diagram

## 🔧 Image Optimization

### Tools for Optimization
- **TinyPNG**: Compress images while maintaining quality
- **ImageOptim**: Mac tool for image compression
- **Squoosh**: Google's web-based image optimizer

### Best Practices
- Use WebP format for better compression (with JPG fallback)
- Keep file sizes under 500KB
- Use descriptive alt text for accessibility
- Test images on different devices

## 🚀 After Adding Images

1. **Test locally**:
   ```bash
   # Open the portfolio in your browser
   open index.html
   ```

2. **Commit changes**:
   ```bash
   git add images/
   git commit -m "Add profile and project images"
   git push
   ```

3. **Verify on GitHub Pages**:
   - Check that images load correctly
   - Ensure they look good on mobile devices

## 🆘 Fallback Behavior

If images are missing, the portfolio will:
- Show appropriate icons as placeholders
- Maintain the same layout and functionality
- Still look professional and complete

## 📱 Mobile Considerations

- Images are responsive and will scale appropriately
- Profile photo maintains circular shape on all devices
- Project images have hover effects on desktop
- All images have proper alt text for accessibility

---

**Need help?** The portfolio is designed to work perfectly even without images, so you can deploy it immediately and add images later!
