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

### Code Genarate by AI (CHatGPT)

```
private void setWallpaperAI() {
        Bitmap bitmap = ((BitmapDrawable) full_images.getDrawable()).getBitmap();
        WallpaperManager wallpaperManager = WallpaperManager.getInstance(SetWallpaper.this);
        try {
            wallpaperManager.setBitmap(bitmap);
            Toast.makeText(getApplicationContext(), "Wallpaper Set Successful", Toast.LENGTH_SHORT).show();
        } catch (IOException e) {
            e.printStackTrace();
        }
    }
```
