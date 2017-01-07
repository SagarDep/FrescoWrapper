# FrescoWapper
wapper fresco like uil imageload


Example:
```java
ImageLoagerWapper.getInstance().load(view, url);

ImageLoagerWapper.getInstance().load(view, url, config);

ImageLoagerWapper.getInstance().load(view, url, config, new IDisplayImageListener<ImageInfo>() {
            
            @Override
            public void onSuccess(ImageInfo result, Animatable animatable) {
                //do someting
            }

            @Override
            public void onFailure(Throwable throwable) {
                //do someting
            }
        });
        
ImageLoagerWapper.getInstance().load(url, new SimpleDownloaderListener(){

            @Override
            public void onSuccess(Bitmap result) {
                super.onSuccess(result);
            }

            @Override
            public void onFailure(Throwable throwable) {
                super.onFailure(throwable);
            }

            @Override
            public void onProgress(float progress) {
                super.onProgress(progress);
            }
        });
        
ImageLoagerWapper.getInstance().load(url, width, height, new SimpleDownloaderListener(){

            @Override
            public void onSuccess(Bitmap result) {
                super.onSuccess(result);
            }

            @Override
            public void onFailure(Throwable throwable) {
                super.onFailure(throwable);
            }

            @Override
            public void onProgress(float progress) {
                super.onProgress(progress);
            }
        });
```




![](https://github.com/tgithubc/FrescoWapper/raw/master/demo_pic/25063B8D-2890-427B-BC46-3F1AEDD83A17.png) 
