# Glide-Circle-Border-transformation
This code can be used to transform image into circular image with a circular border.Border size and colour can be changed directly  by tweeking the code.


Usage:-

                            Glide
                            .with(CONTEXT)
                            .load(IMAGE URL HERE)
                            .override(IMAGE_WIDTH, IMAGE_HEIGHT)
                            .transform(new CircularTransformWhite(CONTEXT)
                            .into(IMAGE_VIEW);
                            
License
Please review below licence from the owner of GLide
https://github.com/bumptech/glide/blob/master/LICENSE
