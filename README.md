# Portfolio Blog Data Source

> **Status:** 🚧 Project Ongoing

This Laravel application serves as the backend data source and API for the blog section of my portfolio website at [karllouiserito.netlify.app](https://karllouiserito.netlify.app/).

## About This Project

This project is built with Laravel to provide a robust, scalable backend solution for managing and delivering blog content to my portfolio website. It handles content creation, storage, and serves data through a RESTful API that my frontend portfolio consumes.

## Key Features

- RESTful API for blog content delivery
- Content management system for blog posts
- Image and media handling
- Category and tag management
- SEO-friendly content structure
- Secure authentication for content management

## Tech Stack

- **Framework:** Laravel
- **Database:** SQLite
- **API:** RESTful architecture
- **Frontend Integration:** Consumed by [karllouiserito.netlify.app](https://karllouiserito.netlify.app/)

## Project Status

This project is currently under active development. Features are being added and refined regularly to enhance the blog functionality on my portfolio website.

### Planned Features

- [ ] Advanced content filtering and search
- [ ] Draft and scheduled publishing
- [ ] Content versioning
- [ ] Analytics integration
- [ ] Enhanced media management

## Local Development

```bash
# Clone the repository
git clone <repository-url>

# Install dependencies
composer install

# Copy environment file
cp .env.example .env

# Generate application key
php artisan key:generate

# Run migrations
php artisan migrate

# Start development server
php artisan serve
```

## API Documentation

API documentation will be available as the project progresses. The API provides endpoints for:

- Blog posts (CRUD operations)
- Categories and tags
- Media files
- Search and filtering

## Portfolio Website

Visit my portfolio at [karllouiserito.netlify.app](https://karllouiserito.netlify.app/) to see this data source in action.

## Contact

For questions or collaboration opportunities, feel free to reach out through my portfolio website.

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

---

**Note:** This is an active development project and may undergo significant changes as new features are implemented and existing ones are refined.