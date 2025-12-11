# Flutter E-Commerce Portfolio

A modern Flutter web portfolio showcasing a complete e-commerce UI flow with professional design and smooth navigation. This project demonstrates best practices in Material Design 3, responsive layouts, and user-centered design patterns.

## Features

### 6 Complete Screens
- **Home**: Portfolio landing page with hero section, project showcase, design highlights, and customer journey blueprint
- **Catalog**: Product grid with 6 demo products, search-optimized layout, and quick actions
- **Product Detail**: Detailed product view with image gallery, specifications, highlights, and dual CTAs
- **Shopping Cart**: Line items with quantity controls, recommended add-ons, and live order summary
- **Checkout**: 3-step form (Contact → Shipping → Payment) with order review sidebar
- **Order Confirmation**: Success state with order tracking and next-best actions

### Design System
- **Typography**: Google Fonts Manrope (weights 600-800) for visual hierarchy
- **Colors**: Teal primary (#0F766E), light slate surface (#F8FAFC)
- **Components**: Reusable cards, badges, buttons with 8px spacing system
- **Navigation**: Named routes with fade transitions (240ms)
- **Responsive**: Max-width constrained layouts (1200px) with flexible grids

## Getting Started

### Prerequisites
- Flutter SDK 3.10.1 or higher
- Dart 3.10.1 or higher

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd portfolio-upwork
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run on web:
```bash
flutter run -d chrome
```

Or for production build:
```bash
flutter build web
```

## Project Structure

```
lib/
├── main.dart          # Complete app with 6 screens, navigation, and theming
```

### Key Components
- `PortfolioApp`: Root app with theme and routing configuration
- `PageShell`: Layout wrapper with AppTopBar and FAB
- `AppTopBar`: Branded navigation bar with 5 nav items
- Screen classes: `HomeScreen`, `CatalogScreen`, `ProductDetailScreen`, `CartScreen`, `CheckoutScreen`, `OrderConfirmationScreen`
- Helper widgets: `_ProductCard`, `_CartLineItem`, `_OrderSummary`, `_FieldCard`, and more

### Navigation Routes
- `/` - Home screen
- `/catalog` - Product catalog
- `/product` - Product detail (with product argument)
- `/cart` - Shopping cart
- `/checkout` - Checkout form
- `/confirmation` - Order confirmation

## Design Highlights

- **Accessibility**: Semantic markup, proper contrast ratios, keyboard navigation
- **Performance**: Optimized widget tree, efficient rebuilds
- **Maintainability**: Modular component structure, clear naming conventions
- **UX Patterns**: Loading states, empty states, success feedback
- **E-commerce Best Practices**: Clear CTAs, trust signals, friction-free checkout

## Demo Products

6 lifestyle products across categories:
1. Aurora Chair (Furniture) - $129.99
2. Lumen Desk Lamp (Lighting) - $89.99
3. North Tote (Accessories) - $59.99
4. Tempo Sneakers (Footwear) - $119.99
5. Haven Throw (Home) - $49.99
6. Peak Bottle (Drinkware) - $34.99

## Technologies

- **Flutter 3.10+**: Cross-platform UI framework
- **Material Design 3**: Modern design language
- **Google Fonts**: Manrope typography
- **Dart**: Programming language

## License

This project is a portfolio demonstration.

