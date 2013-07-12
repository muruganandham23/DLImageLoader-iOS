DLImageLoader-iOS
=================

Image Loader for ios (downloading and caching images).

// ===  Sample of using DLImageLoader  === //

>Connect DLImageLoader in your .m file:

<pre>
#import "DLImageLoader.h"
</pre>

>After that, call image loading:

<pre>
[DLImageLoader loadImageFromURL:@"image_url_here"
                      completed:^(NSError *error, NSData *imgData) {
                      	if (error == nil) {
                      		// if we have no errors
                      	} else {
                      		// if we got error when load image
                        }
                    }];
</pre>

// === Sample is in DLImageLoader Demo == //