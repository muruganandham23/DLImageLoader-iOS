DLImageLoader-iOS
=================

Image Loader for ios

// ===  Sample of using DLImageLoader  === //

>Connect DLImageLoader in your .m file:

#import "DLImageLoader.h"

>After that, call image loading:

[DLImageLoader loadImageFromURL:@"image_url_here"
                      completed:^(NSError *error, NSData *imgData) {
                      	if (error == nil) {
                      		// if we have no errors
                      	} else {
                      		// if we got error when load image
                        }
                    }];