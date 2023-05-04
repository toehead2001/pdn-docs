# View Menu

The View menu contains commands that are used to change the way the image or workspace are presented. These commands do not alter the image itself, only the way it is displayed.

<figure markdown>
  ![View Menu](https://www.getpaint.net/doc/latest/images/menus/view/viewmenu.png)
  <figcaption>View Menu</figcaption>
</figure>

## ![Zoom In](https://www.getpaint.net/doc/latest/images/Icons/View/MenuViewZoomInIcon.192.png) Zoom In

This zooms in on the image. This has the appearance of magnifying it.  The amount of magnification is increased in fixed steps (e.g., 100%, 150%, 200%, 300%, 400%, 500%, 600%, 800%, 1000%, 1200%, 1400%, 1600%, 2000%, 2400%, 2800%, 3200%, 4000%, 4800%, 5600%, 6400%).

## ![Zoom Out](https://www.getpaint.net/doc/latest/images/Icons/View/MenuViewZoomOutIcon.192.png) Zoom Out

This zooms out from the image. This has the appearance of reducing the image or viewing it from further away.  The amount of zoom reduces in fixed steps The amount of magnification is increased in fixed steps (e.g., 100%, 67%, 50%, 33%, 25%, 20%....).

## ![Zoom to Window](https://www.getpaint.net/doc/latest/images/Icons/View/MenuViewZoomToWindowIcon.192.png) Zoom to Window

This command zooms the image to the limits of the Editing Window or to full size.

If the image is larger than the Editing Window at 100%, it will be reduced to fit within the Editing Window.  If the image is smaller than the Editing Window at 100% it will be shown full size.

## ![https://www.getpaint.net/doc/latest/images/Icons/View/MenuViewZoomToSelectionIcon.192.png](https://www.getpaint.net/doc/latest/images/Icons/View/MenuViewZoomInIcon.192.png) Zoom to Selection

This menu command increases the view size of any active selection until the bounding rectangle reaches the limit of the viewable area.  In other words, it zooms the selection to maximally fit within the Editing Window.

## ![Actual Size](https://www.getpaint.net/doc/latest/images/Icons/View/MenuViewActualSizeIcon.192.png) Actual Size

This sets the zoom level to 100%. Each pixel on the screen will correspond exactly with one pixel in the active layer.

## ![Pixel Grid](https://www.getpaint.net/doc/latest/images/Icons/View/MenuViewGridIcon.192.png) Pixel Grid

The Pixel Grid overlays the current image with a grid where each cell is exactly one pixel in size.  The Pixel Grid is particularly useful when zoomed-in on an image and precise per-pixel editing is required.

The same menu command can be used to toggle the grid off again. There is also an icon in the Tool Bar which performs the same actions.

!!! Warning
    The Pixel Grid is not visible below 200% magnification.

These images show the pixel grid in action...

<figure markdown>
  ![Original image at full size](https://www.getpaint.net/doc/latest/images/menus/view/gridorigin.png)
  <figcaption>Original image at full size</figcaption>
</figure>

<figure markdown>
  ![OPixel Grid active on enlarged section.](https://www.getpaint.net/doc/latest/images/menus/view/grid.png)
  <figcaption>Pixel Grid active on enlarged section.</figcaption>
</figure>

## ![Rulers](https://www.getpaint.net/doc/latest/images/Icons/View/MenuViewRulersIcon.192.png) Rulers

This menu command shows or hides rulers along the top and left edges of the image canvas. There is a corresponding icon in the Tool Bar.

The Rulers can help when aligning image elements, making measurements or adjusting an image to a specific size. The rulers are always set to the current Units of Measurement (see below).

When a selection is active, its bounding rectangle will be highlighted in the rulers, making it easier to measure. The cursor position is also shown in the rulers making it easier to accurately apply other tools.

<figure markdown>
  ![Rulers](https://www.getpaint.net/doc/latest/images/menus/view/ViewMenu-Rulers.png)
  <figcaption>Rulers</figcaption>
</figure>

### Units of Measurement

<figure markdown>
  ![Units of Measurement](https://www.getpaint.net/doc/latest/images/menus/view/view-unitsofmeasurement.png)
  <figcaption>Units of Measurement</figcaption>
</figure>

This set of three checkboxes define which units of measurement paint.net will use.  The units define how image coordinates are presented in various areas of the user interface (including the Rulers and the Status Bar).

The default unit of measurement is pixels (as shown). If inches or centimeters are selected, extra calculations are performed to convert pixel measurements into inches and centimeters.  These calculations are based off the image's DPI settings, which can be adjusted in the Image → Resize dialog.

The units of measurement can also be set via the Status Bar.

<figure markdown>
  ![Units of Measurement in the Status Bar](https://www.getpaint.net/doc/latest/images/mainwindow/StatusBar/statusbarUnits.png)
  <figcaption>Units of Measurement</figcaption>
</figure>
