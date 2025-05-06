# 🕸️ Sigma Website Web Scraper (Efficient Python Notebook)

This project is a **highly efficient web scraper** built using Python in a Jupyter Notebook. It extracts product data from the Sigma website with optimal performance, clean code structure, and minimal resource usage — making it a solid choice for scalable and customizable scraping tasks.

## 🚀 Why This Notebook Is Efficient

✅ **Fast Page Parsing** – Uses `requests` for HTTP calls and `BeautifulSoup` for lightweight HTML parsing.  
✅ **Optimized Looping** – Efficiently loops through pages and products without redundancy.  
✅ **Clean Data Handling** – Stores scraped data in a structured `pandas` DataFrame.  
✅ **Easy to Modify** – Well-commented, modular code allows easy customization (e.g., for different product categories).  
✅ **Export Ready** – Outputs data directly to a CSV file for further analysis or integration.

## 📦 Extracted Data

The notebook extracts the following for each product:

- **Product Name**
- **Product Link**
- **Product Description**

## 🧰 Tools & Libraries Used

- `requests` – for sending HTTP requests  
- `BeautifulSoup` – for HTML parsing  
- `pandas` – for tabular data processing  
- `csv` – for exporting the results

## 📂 How It Works

1. **Send HTTP Request** to the target Sigma product category page.
2. **Parse HTML Content** using BeautifulSoup.
3. **Loop Through Product Listings** to extract name, link, and description.
4. **Store Data** in a pandas DataFrame.
5. **Export Results** to a CSV file.

## 🛠️ How to Run

1. Open the notebook: `scraping_sigma_website.ipynb`
2. Run all cells in order.
3. A CSV file named `sigma_products.csv` will be generated with the results.

## 📌 Output Sample

Here’s a sample of the actual output:

| Product Name | Product Link | Product Description |
|--------------|--------------|---------------------|
| Aldrich® Chemistry | https://www.sigmaaldrich.com/US/en/products/aldrich | Chemistry Products |
| Supelco® Analytical | https://www.sigmaaldrich.com/US/en/products/supelco | Analytical Products |

> ✅ The output is clean, structured, and ready for use in analysis or applications.

## ⚠️ Legal Note

This scraper is for educational purposes only. Please ensure you are authorized to scrape content from the Sigma website and always respect their [robots.txt](https://www.sigmaaldrich.com/robots.txt) and terms of use.

## 📄 License

Open for academic and non-commercial use under the MIT License.
