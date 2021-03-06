<a name="ngStrapLightbox"></a>
## ngStrapLightbox : <code>object</code>
**Kind**: global namespace

* [ngStrapLightbox](#ngStrapLightbox) : <code>object</code>
  * [.ImageLoader](#ngStrapLightbox.ImageLoader)
    * [.load](#ngStrapLightbox.ImageLoader.load) ⇒ <code>Promise</code>
  * [.Lightbox](#ngStrapLightbox.Lightbox)
    * [.templateUrl](#ngStrapLightbox.Lightbox.templateUrl) : <code>String</code>
    * [.fullScreenMode](#ngStrapLightbox.Lightbox.fullScreenMode) : <code>Boolean</code>
    * [.getImageUrl](#ngStrapLightbox.Lightbox.getImageUrl) ⇒ <code>String</code>
    * [.getImageCaption](#ngStrapLightbox.Lightbox.getImageCaption) ⇒ <code>String</code>
    * [.calculateImageDimensionLimits](#ngStrapLightbox.Lightbox.calculateImageDimensionLimits) ⇒ <code>Object</code>
    * [.calculateModalDimensions](#ngStrapLightbox.Lightbox.calculateModalDimensions) ⇒ <code>Object</code>
    * [.isVideo](#ngStrapLightbox.Lightbox.isVideo) ⇒ <code>Boolean</code>
    * [.isSharedVideo](#ngStrapLightbox.Lightbox.isSharedVideo) ⇒ <code>Boolean</code>
    * [.images](#ngStrapLightbox.Lightbox.images) : <code>Array</code>
    * [.index](#ngStrapLightbox.Lightbox.index) : <code>Number</code>
    * [.keyboardNavEnabled](#ngStrapLightbox.Lightbox.keyboardNavEnabled) : <code>Boolean</code>
    * [.image](#ngStrapLightbox.Lightbox.image) : <code>\*</code>
    * [.modalInstance](#ngStrapLightbox.Lightbox.modalInstance) : <code>Object</code>
    * [.imageUrl](#ngStrapLightbox.Lightbox.imageUrl) : <code>String</code>
    * [.imageCaption](#ngStrapLightbox.Lightbox.imageCaption) : <code>String</code>
    * [.loading](#ngStrapLightbox.Lightbox.loading) : <code>Boolean</code>
    * [.openModal](#ngStrapLightbox.Lightbox.openModal) ⇒ <code>Object</code>
    * [.closeModal](#ngStrapLightbox.Lightbox.closeModal) : <code>function</code>
    * [.setImage](#ngStrapLightbox.Lightbox.setImage) : <code>function</code>
    * [.firstImage](#ngStrapLightbox.Lightbox.firstImage) : <code>function</code>
    * [.prevImage](#ngStrapLightbox.Lightbox.prevImage) : <code>function</code>
    * [.nextImage](#ngStrapLightbox.Lightbox.nextImage) : <code>function</code>
    * [.lastImage](#ngStrapLightbox.Lightbox.lastImage) : <code>function</code>
    * [.setImages](#ngStrapLightbox.Lightbox.setImages) : <code>function</code>
  * [.lightboxSrc](#ngStrapLightbox.lightboxSrc)

<a name="ngStrapLightbox.ImageLoader"></a>
### ngStrapLightbox.ImageLoader
Service for loading an image.

**Kind**: static class of <code>[ngStrapLightbox](#ngStrapLightbox)</code>
<a name="ngStrapLightbox.ImageLoader.load"></a>
#### ImageLoader.load ⇒ <code>Promise</code>
Load the image at the given URL.

**Kind**: static property of <code>[ImageLoader](#ngStrapLightbox.ImageLoader)</code>
**Returns**: <code>Promise</code> - A $q promise that resolves when the image has loaded
  successfully.

| Param | Type |
| --- | --- |
| url | <code>String</code> |

<a name="ngStrapLightbox.Lightbox"></a>
### ngStrapLightbox.Lightbox
Lightbox service.

**Kind**: static class of <code>[ngStrapLightbox](#ngStrapLightbox)</code>

* [.Lightbox](#ngStrapLightbox.Lightbox)
  * [.templateUrl](#ngStrapLightbox.Lightbox.templateUrl) : <code>String</code>
  * [.fullScreenMode](#ngStrapLightbox.Lightbox.fullScreenMode) : <code>Boolean</code>
  * [.getImageUrl](#ngStrapLightbox.Lightbox.getImageUrl) ⇒ <code>String</code>
  * [.getImageCaption](#ngStrapLightbox.Lightbox.getImageCaption) ⇒ <code>String</code>
  * [.calculateImageDimensionLimits](#ngStrapLightbox.Lightbox.calculateImageDimensionLimits) ⇒ <code>Object</code>
  * [.calculateModalDimensions](#ngStrapLightbox.Lightbox.calculateModalDimensions) ⇒ <code>Object</code>
  * [.isVideo](#ngStrapLightbox.Lightbox.isVideo) ⇒ <code>Boolean</code>
  * [.isSharedVideo](#ngStrapLightbox.Lightbox.isSharedVideo) ⇒ <code>Boolean</code>
  * [.images](#ngStrapLightbox.Lightbox.images) : <code>Array</code>
  * [.index](#ngStrapLightbox.Lightbox.index) : <code>Number</code>
  * [.keyboardNavEnabled](#ngStrapLightbox.Lightbox.keyboardNavEnabled) : <code>Boolean</code>
  * [.image](#ngStrapLightbox.Lightbox.image) : <code>\*</code>
  * [.modalInstance](#ngStrapLightbox.Lightbox.modalInstance) : <code>Object</code>
  * [.imageUrl](#ngStrapLightbox.Lightbox.imageUrl) : <code>String</code>
  * [.imageCaption](#ngStrapLightbox.Lightbox.imageCaption) : <code>String</code>
  * [.loading](#ngStrapLightbox.Lightbox.loading) : <code>Boolean</code>
  * [.openModal](#ngStrapLightbox.Lightbox.openModal) ⇒ <code>Object</code>
  * [.closeModal](#ngStrapLightbox.Lightbox.closeModal) : <code>function</code>
  * [.setImage](#ngStrapLightbox.Lightbox.setImage) : <code>function</code>
  * [.firstImage](#ngStrapLightbox.Lightbox.firstImage) : <code>function</code>
  * [.prevImage](#ngStrapLightbox.Lightbox.prevImage) : <code>function</code>
  * [.nextImage](#ngStrapLightbox.Lightbox.nextImage) : <code>function</code>
  * [.lastImage](#ngStrapLightbox.Lightbox.lastImage) : <code>function</code>
  * [.setImages](#ngStrapLightbox.Lightbox.setImages) : <code>function</code>

<a name="ngStrapLightbox.Lightbox.templateUrl"></a>
#### Lightbox.templateUrl : <code>String</code>
Template URL passed into `$modal.open()`.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
<a name="ngStrapLightbox.Lightbox.fullScreenMode"></a>
#### Lightbox.fullScreenMode : <code>Boolean</code>
Whether images should be scaled to the maximum possible dimensions.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
<a name="ngStrapLightbox.Lightbox.getImageUrl"></a>
#### Lightbox.getImageUrl ⇒ <code>String</code>
**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
**Returns**: <code>String</code> - The URL of the given image.

| Param | Type | Description |
| --- | --- | --- |
| image | <code>\*</code> | An element in the array of images. |

<a name="ngStrapLightbox.Lightbox.getImageCaption"></a>
#### Lightbox.getImageCaption ⇒ <code>String</code>
**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
**Returns**: <code>String</code> - The caption of the given image.

| Param | Type | Description |
| --- | --- | --- |
| image | <code>\*</code> | An element in the array of images. |

<a name="ngStrapLightbox.Lightbox.calculateImageDimensionLimits"></a>
#### Lightbox.calculateImageDimensionLimits ⇒ <code>Object</code>
Calculate the max and min limits to the width and height of the displayed
  image (all are optional). The max dimensions override the min
  dimensions if they conflict.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
**Returns**: <code>Object</code> - May optionally contain the properties `minWidth`,
  `minHeight`, `maxWidth`, and `maxHeight`.

| Param | Type | Description |
| --- | --- | --- |
| dimensions | <code>Object</code> | Contains the properties `windowWidth`,   `windowHeight`, `imageWidth`, and `imageHeight`. |

<a name="ngStrapLightbox.Lightbox.calculateModalDimensions"></a>
#### Lightbox.calculateModalDimensions ⇒ <code>Object</code>
Calculate the width and height of the modal. This method gets called
  after the width and height of the image, as displayed inside the modal,
  are calculated.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
**Returns**: <code>Object</code> - Must contain the properties `width` and `height`.

| Param | Type | Description |
| --- | --- | --- |
| dimensions | <code>Object</code> | Contains the properties `windowWidth`,   `windowHeight`, `imageDisplayWidth`, and `imageDisplayHeight`. |

<a name="ngStrapLightbox.Lightbox.isVideo"></a>
#### Lightbox.isVideo ⇒ <code>Boolean</code>
**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
**Returns**: <code>Boolean</code> - Whether the provided element is a video.

| Param | Type | Description |
| --- | --- | --- |
| image | <code>\*</code> | An element in the array of images. |

<a name="ngStrapLightbox.Lightbox.isSharedVideo"></a>
#### Lightbox.isSharedVideo ⇒ <code>Boolean</code>
**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
**Returns**: <code>Boolean</code> - Whether the provided element is a video that is to be
  embedded with an external service like YouTube. By default, this is
  determined by the url not ending in `.mp4`, `.ogg`, or `.webm`.

| Param | Type | Description |
| --- | --- | --- |
| image | <code>\*</code> | An element in the array of images. |

<a name="ngStrapLightbox.Lightbox.images"></a>
#### Lightbox.images : <code>Array</code>
Array of all images to be shown in the lightbox (not `Image` objects).

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
<a name="ngStrapLightbox.Lightbox.index"></a>
#### Lightbox.index : <code>Number</code>
The index in the `Lightbox.images` aray of the image that is currently
  shown in the lightbox.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
<a name="ngStrapLightbox.Lightbox.keyboardNavEnabled"></a>
#### Lightbox.keyboardNavEnabled : <code>Boolean</code>
Whether keyboard navigation is currently enabled for navigating through
  images in the lightbox.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
<a name="ngStrapLightbox.Lightbox.image"></a>
#### Lightbox.image : <code>\*</code>
The image currently shown in the lightbox.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
<a name="ngStrapLightbox.Lightbox.modalInstance"></a>
#### Lightbox.modalInstance : <code>Object</code>
The UI Bootstrap modal instance. See {@link
  http://angular-ui.github.io/bootstrap/#/modal}.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
<a name="ngStrapLightbox.Lightbox.imageUrl"></a>
#### Lightbox.imageUrl : <code>String</code>
The URL of the current image. This is a property of the service rather
  than of `Lightbox.image` because `Lightbox.image` need not be an
  object, and besides it would be poor practice to alter the given
  objects.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
<a name="ngStrapLightbox.Lightbox.imageCaption"></a>
#### Lightbox.imageCaption : <code>String</code>
The optional caption of the current image.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
<a name="ngStrapLightbox.Lightbox.loading"></a>
#### Lightbox.loading : <code>Boolean</code>
Whether an image is currently being loaded.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
<a name="ngStrapLightbox.Lightbox.openModal"></a>
#### Lightbox.openModal ⇒ <code>Object</code>
Open the lightbox modal.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
**Returns**: <code>Object</code> - The created UI Bootstrap modal instance.

| Param | Type | Description |
| --- | --- | --- |
| newImages | <code>Array</code> | An array of images. Each image may be of   any type. |
| newIndex | <code>Number</code> | The index in `newImages` to set as the   current image. |
| modalParams | <code>Object</code> | Custom params for the angular UI   bootstrap modal (in $modal.open()). |

<a name="ngStrapLightbox.Lightbox.closeModal"></a>
#### Lightbox.closeModal : <code>function</code>
Close the lightbox modal.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>

| Param | Type | Description |
| --- | --- | --- |
| result | <code>\*</code> | This argument can be useful if the modal promise   gets handler(s) attached to it. |

<a name="ngStrapLightbox.Lightbox.setImage"></a>
#### Lightbox.setImage : <code>function</code>
This method can be used in all methods which navigate/change the
  current image.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>

| Param | Type | Description |
| --- | --- | --- |
| newIndex | <code>Number</code> | The index in the array of images to set as   the new current image. |

<a name="ngStrapLightbox.Lightbox.firstImage"></a>
#### Lightbox.firstImage : <code>function</code>
Navigate to the first image.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
<a name="ngStrapLightbox.Lightbox.prevImage"></a>
#### Lightbox.prevImage : <code>function</code>
Navigate to the previous image.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
<a name="ngStrapLightbox.Lightbox.nextImage"></a>
#### Lightbox.nextImage : <code>function</code>
Navigate to the next image.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
<a name="ngStrapLightbox.Lightbox.lastImage"></a>
#### Lightbox.lastImage : <code>function</code>
Navigate to the last image.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>
<a name="ngStrapLightbox.Lightbox.setImages"></a>
#### Lightbox.setImages : <code>function</code>
Call this method to set both the array of images and the current image
  (based on the current index). A use case is when the image collection
  gets changed dynamically in some way while the lightbox is still
  open.

**Kind**: static property of <code>[Lightbox](#ngStrapLightbox.Lightbox)</code>

| Param | Type | Description |
| --- | --- | --- |
| newImages | <code>Array</code> | The new array of images. |

<a name="ngStrapLightbox.lightboxSrc"></a>
### ngStrapLightbox.lightboxSrc
This attribute directive is used in an `<img>` element in the
  modal template in place of `src`. It handles resizing both the `<img>`
  element and its relevant parent elements within the modal.

**Kind**: static class of <code>[ngStrapLightbox](#ngStrapLightbox)</code>
