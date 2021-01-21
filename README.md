# ImageBuilder
Component for php and more comfortable work with images.

Class "ImageBuilder" contains these methods:
        can_upload - Возможно ли загрузить фото(return true or false)
        make_upload - uploads a photo to the file system (and returning full path of photo)
        delete - deleting photo (will return true if result is success)        
        wAndB - makes photo black and white
        flip - mirror reflection
        rotate - Rotates the photo
        negative - Applying a negative filter
        resize - change size of photo
        openPhoto - open the file in php from the system file using the desired method
