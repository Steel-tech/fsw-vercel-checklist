# FSW NREL EMAPS Inspection Checklist

A professional web-based inspection checklist application for **Flawless Steel Welding, LLC** designed for NREL EMAPS (National Renewable Energy Laboratory Equipment Maintenance and Performance Standards) inspections.

## 🌐 Live Application
**Production URL**: https://fsw-inspection-checklist.vercel.app

## 📋 Features

- **Professional Interface**: Clean, branded design with company styling
- **Interactive Checklist**: Comprehensive inspection items with checkboxes and notes
- **Photo Upload**: Ability to attach photos to inspection sections
- **Print-Friendly**: Optimized layout for professional report printing
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Data Persistence**: Local storage of inspection data
- **Project Information**: Detailed project metadata capture

## 🛠 Technology Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Deployment**: Vercel (Static Site)
- **Styling**: Custom CSS with professional branding
- **Storage**: LocalStorage for client-side data persistence

## 🚀 Deployment

This application is automatically deployed to Vercel from the main branch.

### Live URLs:
- Primary: https://fsw-inspection-checklist.vercel.app
- Alternative: https://fsw-inspection-checklist-fsw-iron-task.vercel.app

### Manual Deployment
```bash
# Install Vercel CLI (if needed)
npm install -g vercel

# Deploy to production
vercel --prod
```

## 🏗 Development

### Local Development
```bash
# Start local development server
npm run dev
# Opens on http://localhost:8000
```

### Project Structure
```
fsw-vercel-checklist/
├── index.html          # Main application file
├── package.json        # Project metadata
├── vercel.json         # Vercel deployment configuration
├── .gitignore         # Git ignore rules
└── README.md          # This file
```

## 📄 Project Details

- **Company**: Flawless Steel Welding, LLC
- **Purpose**: NREL EMAPS Inspection Checklist
- **License**: Proprietary
- **Version**: 1.0.0

## 🔧 Configuration

The application is configured for static deployment with:
- Vercel static file serving
- Automatic routing to index.html
- Production-ready caching headers

## 📱 Usage

1. Open the live application URL
2. Fill in project information at the top
3. Work through each inspection section
4. Check off completed items and add notes as needed
5. Upload photos for documentation
6. Print the completed checklist for records

## 🔒 Security & Privacy

- All data is stored locally in the browser
- No data is transmitted to external servers
- Photos are handled client-side only
- Suitable for sensitive inspection data

## 📞 Support

For technical support or questions about this inspection checklist application, contact Flawless Steel Welding, LLC.

---
*Built with ❤️ for professional steel welding inspections*
