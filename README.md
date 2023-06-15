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
