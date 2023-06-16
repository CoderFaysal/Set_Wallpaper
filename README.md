# Set Wallpaper

```
private void setWallpaperAuto() {
        WallpaperManager wallpaperManager = WallpaperManager.getInstance(getApplicationContext());
        try {
            wallpaperManager.setBitmap(MY_BITMAP);
            Toast.makeText(getApplicationContext(), "Wallpaper set Successful", Toast.LENGTH_SHORT).show();
        } catch (IOException ex) {
            ex.printStackTrace();
        }
    }
```

### Code Genaret by AI (CHatGPT)

```
Bitmap bitmap = ((BitmapDrawable) imageView.getDrawable()).getBitmap();
                WallpaperManager wallpaperManager = WallpaperManager.getInstance(MainActivity.this);
                try {
                    wallpaperManager.setBitmap(bitmap);
                    // Show a success message or perform any other actions
                } catch (IOException e) {
                    e.printStackTrace();
                    // Handle error if wallpaper setting fails
                }
```
