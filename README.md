# 🎨 Art Supply Inventory - Complete Pencil Colors Database

A comprehensive web application for tracking your colored pencil collection with detailed color information, lightfastness ratings, and inventory management.

## 🌟 Features

- **Complete Color Database**: Over 400+ colors from premium pencil sets
  - **Derwent**: ProColour, Lightfast, Coloursoft
  - **Caran d'Ache**: Luminance 6901, Neocolor II, Pablo
- **Interactive Color Swatches**: Visual color previews with hex codes
- **Lightfastness Ratings**: Detailed lightfastness information with standardized ratings
- **Personal Inventory Tracking**: Check off colors you own and track completion rates
- **Advanced Filtering**: Filter by brand, set, lightfastness rating, or ownership status
- **Search Functionality**: Find colors by name, code, or number
- **Export/Import**: Save and restore your inventory data
- **Multiple Export Formats**: Download as CSV, JSON, or copy to clipboard for Excel

## 🚀 Live Demo

Visit the live application: [https://yourusername.github.io/ArtSupplyInventory/](https://yourusername.github.io/ArtSupplyInventory/)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with gradients, flexbox, and responsive design
- **Vanilla JavaScript**: Dynamic functionality and data management
- **Local Storage**: Client-side data persistence
- **JSON Data**: Structured color information storage

## 📊 Data Structure

Each color entry contains:
- `code`: Unique product code
- `name`: Color name
- `number`: Manufacturer's color number
- `set`: Pencil set name
- `lightfastness`: Lightfastness rating (1-8 or standardized ratings)
- `lightfastnessType`: Rating system used (BW, ASTM, Blue Wool, etc.)
- `hexColor`: Approximate hex color value

## 🎯 Usage

### Basic Operations
1. **Browse Colors**: View all colors in an organized table format
2. **Filter by Set**: Select specific pencil sets from the dropdown
3. **Search**: Use the search box to find specific colors
4. **Track Ownership**: Check the boxes for colors you own

### Inventory Management
1. **Export Inventory**: Save your collection data as JSON
2. **Import Inventory**: Load previously saved inventory data
3. **View Statistics**: See completion rates and collection progress
4. **Clear Inventory**: Reset all ownership data

### Data Export
1. **CSV Export**: Download for spreadsheet applications
2. **JSON Export**: Technical format with complete data
3. **Clipboard Copy**: Tab-separated format for Excel

## 🔧 Local Development

### Running Locally
Due to browser security restrictions, you'll need a local server to run the application:

#### Option 1: Python
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Option 2: Node.js
```bash
npx serve .
# or
npm install -g http-server
http-server
```

#### Option 3: VS Code
Install the "Live Server" extension and right-click on `index.html` → "Open with Live Server"

### File Structure
```
ArtSupplyInventory/
├── index.html                     # Main application
├── ArtSupplyInventory.html        # Original version (backup)
├── README.md                      # This file
├── derwent-procolour-json.json    # Derwent ProColour data
├── derwent-lightfast-json.json    # Derwent Lightfast data
├── derwent-coloursoft-json.json   # Derwent Coloursoft data
├── caran-luminance-json.json      # Caran d'Ache Luminance data
├── caran-neocolor-json.json       # Caran d'Ache Neocolor II data
└── caran-pablo-json.json          # Caran d'Ache Pablo data
```

## 🎨 Color Sets Included

### Derwent
- **ProColour (72 colors)**: Professional quality with excellent blending
- **Lightfast (100 colors)**: Exceptional lightfastness ratings
- **Coloursoft (72 colors)**: Soft, velvety texture for vibrant results

### Caran d'Ache
- **Luminance 6901 (76 colors)**: Premium lightfast colored pencils
- **Neocolor II (84 colors)**: Water-soluble wax pastels
- **Pablo (120 colors)**: Dry colored pencils with excellent lightfastness

## 📱 Responsive Design

The application is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones
- All modern browsers

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit color data corrections
- Improve the user interface

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Color data compiled from official manufacturer specifications
- Lightfastness ratings based on ASTM and Blue Wool standards
- Special thanks to the art community for color accuracy feedback

---

**Note**: Color swatches are approximations. Actual pencil colors may vary due to display settings and manufacturing variations.
