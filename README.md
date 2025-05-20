# AIBridge – BigBuy Retailer Toolkit

**WooCommerce plugin** for AI-powered BigBuy product import, pricing, and content generation.

---

## What is this?

AIBridge is a WordPress plugin for WooCommerce that automatically imports products from BigBuy, generates product names, descriptions, and images using AI (ChatGPT), and performs dynamic pricing based on currency exchange rates.

---

## Key Features

- Integration with BigBuy API to import products and categories  
- AI-powered product name and description generation (ChatGPT)  
- Multi-language and currency support with exchange rate based pricing  
- Synchronization of BigBuy categories with WooCommerce  
- Currency exchange API integration for price updates  
- Upcoming Pro features: subscription-based AI content generation and pricing  

---

## Installation

1. Upload the plugin folder to `/wp-content/plugins/aibridge-bigbuy-retailer/`  
2. Activate the plugin through the WordPress admin dashboard  
3. Configure your BigBuy API key and currency exchange API in plugin settings  

---

## Usage

- Products are imported and processed automatically either via WP-Cron **or** via WP-CLI, based on configuration  
- Manual trigger available via a button in the WordPress admin interface  
- Filter products by categories  
- Use AI-generated content features (available in Pro version)  

---

## Development

For contributors:  

- Run `composer install` (if applicable)  
- Enter your API keys in the admin panel  
- Explore the `includes/` directory for core plugin functionality  

---

## License

MIT License © 2025 Ágnes Varga

---

## Contact

For questions or support, reach out at https://github.com/GigiCooper
