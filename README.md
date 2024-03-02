# Sole Customer
Sole Customer is a front-end e-commerce store where users can browse and purchase products created by [Sole Admin](https://github.com/Dalton-G/Sole-Admin). Users can browse the featured items, or explore each of the categories from the navbar. Each category also comes with it's filtering options as well. User can preview items, add to cart, and checkout securely using Stripe.

## To Preview

You may visit the deployed website [here](https://sole-customer.vercel.app), or clone this repository and run it using:

```bash
npm run dev
```

## Features
- **🏪 product filtering**: filter by category, colors and size
- **👟 product preview**: don't want to load a full page? just click the preview button!
- **💵 dynamic add-to-cart**: your cart items are saved into your browser's local storage
- **🔗 stripe checkout**: a fully-functional checkout page managed by Stripe

## Technologies used
| Technologies                 | Purpose                              |
|------------------------------|--------------------------------------|
| Next.js                      | main framework                       |
| React, Tailwind, Headless UI | front-end libraries used for styling |
| PostgreSQL                   | open-source relational DBMS          |
| Prisma                       | ORM for generating & executing SQL   |
| Supabase                     | Database host                        |
| Cloudinary                   | Media Upload                         |
| Clerk                        | Authentication                       |
| Stripe                       | Checkout                             |

## Screenshots
![featured_items](https://github.com/Dalton-G/Sole-Customer/blob/master/assets/featured_items.png?raw=true)
![filter_items](https://github.com/Dalton-G/Sole-Customer/blob/master/assets/filter_items.png?raw=true)
![item_preview](https://github.com/Dalton-G/Sole-Customer/blob/master/assets/item_preview.png?raw=true)
![full_product_page](https://github.com/Dalton-G/Sole-Customer/blob/master/assets/full_product_page.png?raw=true)
![shopping_cart](https://github.com/Dalton-G/Sole-Customer/blob/master/assets/shopping_cart.png?raw=true)
![stripe](https://github.com/Dalton-G/Sole-Customer/blob/master/assets/stripe_page.png?raw=true)

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://github.com/Dalton-G/Sole-Customer/blob/main/LICENSE)