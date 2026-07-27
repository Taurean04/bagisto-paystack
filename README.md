# Bagisto Paystack

A lightweight Paystack payment integration for **Bagisto** (Laravel eCommerce).

This package provides a custom payment method implementation for merchants who want to accept Paystack payments in their Bagisto store.

---

## Why this exists

Integrating Paystack into Bagisto can be tricky depending on your Bagisto version and payment flow setup.  
This project was created as a practical implementation to help others get a working integration faster.

---

## Features

- Paystack payment method for Bagisto checkout
- Simple, practical implementation
- Built with Laravel conventions
- Easy to clone and adapt for your own Bagisto project

---

## Built With

- [Laravel](https://laravel.com)
- [Bagisto](https://bagisto.com)
- [Paystack](https://paystack.com)

---

## Getting Started

### Prerequisites

Before using this package, make sure you have:

- PHP and Composer installed
- A working Bagisto installation
- A Paystack account with API keys

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Taurean04/bagisto-paystack.git
cd bagisto-paystack
```

2. Install dependencies (if needed):

```bash
composer install
```

3. Configure your environment variables (example):

```env
PAYSTACK_PUBLIC_KEY=your_public_key
PAYSTACK_SECRET_KEY=your_secret_key
PAYSTACK_PAYMENT_URL=https://api.paystack.co
```

4. Integrate the package into your Bagisto project based on your version-specific payment method setup.

---

## Usage

After setup:

1. Enable the Paystack payment method in your Bagisto admin settings.
2. Place a test order from the storefront.
3. Complete payment via Paystack checkout.
4. Verify order/payment status update in Bagisto.

---

## Project Status

This is a community implementation and may require adjustments for your specific Bagisto version or checkout customization.

---

## Contributing

Contributions are welcome.

If you have improvements:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a pull request

You can also open an issue with the `enhancement` label.

---

## Support

If you run into issues, please open a GitHub issue with:

- Your Bagisto version
- Steps to reproduce
- Error logs/screenshots (if available)

---

## License

Add your license here (for example: MIT).  
If you want, you can create a `LICENSE` file and reference it in this section.
