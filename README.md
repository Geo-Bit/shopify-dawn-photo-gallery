# Shopify Dawn Photo Gallery

## Introduction

This repository provides a custom photo gallery solution for the Shopify Dawn theme. The gallery uses Fancybox to create a responsive, interactive photo gallery with a darkened and blurred background effect when images are viewed in fullscreen mode. This setup is ideal for showcasing product images, portfolio pieces, or any collection of photos.

## Integration/Installation Instructions

Follow these steps to integrate the custom photo gallery into your Shopify store using the Dawn theme.

### 1. Add the Photo Gallery Template

Create a new template in your Shopify store:

1. Navigate to **Online Store** > **Themes**.
2. Click **Actions** > **Edit Code**.
3. Under **Templates**, click **Add a new template**.
4. Choose **page** and name it `photo-gallery`.

### 2. Add the Photo Gallery Code

Replace the content of the newly created `photo-gallery.liquid` file with `src/photo-gallery.liquid` code

### 3. Assign the Template to a Page

1. Navigate to **Online Store** > **Pages**.
2. Click **Add page**.
3. Name the page (e.g., "Gallery").
4. Under **Template suffix**, select `page.photo-gallery`.
5. Click **Save**.

### 4. Add Images

#### Option 1: Using Google Cloud Storage

1. Set **Image Source Type** to **Google Cloud Storage** in the template customizer.
2. Enter your Google Cloud Storage **Bucket Name** (just name, not the full URL).
   - Ensure your bucket and files are publicly accessible.

#### Option 2: Using a List of Image Links

1. Set **Image Source Type** to **List of Links**.
2. Enter the image URLs, one per line, in the **Image URLs** textarea.
3. Click **Save**.

### Option 3: Manually upload files

Coming soon!

## Future Enhancements / Work in Progress

- **Multi-Select Image Picker**: Implement a more efficient way to upload multiple images at once.
- **Image Folder Integration**: Develop a method to dynamically load images from a specific folder on Shopify.
- **Custom Styling Options**: Add customization options for the gallery layout and styles.
- **Additional Lightbox Features**: Explore additional lightbox features and customizations.

## Additional Notes

- Ensure that the image URLs are publicly accessible and correctly formatted.
- Customize the gallery item styles as needed to match your store's design.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
