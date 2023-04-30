# Background Remover

This is a web application that uses Cloudinary's AI to remove the background from images. It is built with Svelte and TypeScript.

## Getting Started

To run the application locally, you will need to create a `.env` file with your Cloudinary API credentials:

```
CLOUD_NAME=your_cloud_name
API_KEY=your_api_key
```

Then, run the following commands:

```
npm install
npm run dev
```

This will start a local development server at http://localhost:5000.

## How to Use

1. Upload an image by clicking the "Upload" button.
2. Wait for the image to be processed by Cloudinary's AI.
3. Download the image with the background removed by clicking the "Download" button.

## Technologies Used

- [Svelte](https://svelte.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Cloudinary AI](https://cloudinary.com/documentation/ai_background_removal_addon)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
