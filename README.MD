**This version of canvas-zoom only works with the March 25th and later versions of the WebUI.**

**If you haven't updated, you can install from this commit** https://github.com/richrobber2/canvas-zoom/tree/33b690c2ccec1bf436d4d37af1c6998209a860b6.

# EN

An extension of [stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

**You can check out the features of this extension in [canvas-zoom-showcase](https://github.com/daswer123/canvas-zoom-showcase)**

Adds the ability to zoom into Inpaint, Sketch, and Inpaint Sketch.

You can edit the hotkeys as you want, to do this, you need to get into the context menu, you need to **right clicking** on the **Inpaint , Sketch and Inpaint Sketch tab, on the image area** and a context me opens where you can configure the hotkeys as you want

The hotkeys only work in the image area, except for the hotkey for moving

Default hotkeys:

**Shift + click or wheel (hold)** - Move canvas

**F (hold)** - Move canvas

**Shift + "+" or Shift + "-"** - Scale canvas ( numpad keys also work )

**Shift + wheel** - Scale canvas

**Ctr + wheel** - Change brush size

**S** - Zoom in on the canvas so that it fits into the screen

**R** - Reset Zoom.

**Q** - Open/Close color panel

**T** - Open color panel right above the mouse. The mouse should be in the image area

**O** - Overlap all elements and back

**Ctr-Z** - Undo last action

**C** - Toggle mask transparency mode ( Works only in Inpaint )

**V** - Toggle brush transparency mode ( Works only in Inpaint )

You can't draw in transparency mode, otherwise there is a chance that one of the lines will be cancelled. Turn off mask transparency mode when you draw. This mode is not stable yet, work will be done to improve it.

**Features**

1. You can fix the color bar wherever you want, for this purpose point the mouse on the place you want and press "T" and then every time you press "Q" the color bar will open in this place. If you click on the button in the right corner, the panel will reset and work as it should.

2. If you zoom in on a picture that is too wide to fit in the window, pressing "S" will magnify it to full screen width without the scroll bar

**Known bugs:**

1. If you constantly switch Sketch, Inpaint, Inpaint Sketch at different zoom levels via the lower buttons, the picture may be cropped. To solve this problem, just delete the picture through the cross and reset through the buttons or manually

2. This is not my bug, the problem is related to webui automatic1111. If you send a picture to Sketch or Inpaint Sketch via buttons, the undo last action on the hotkey and on the button breaks. What to avoid this problem: you can load the picture directly, via drag and drop or via copy and paste.

3. This is not my bug, the problem is with webui automatic1111. If you draw something in Sketch, Inpaint, Inpaint Sketch and then switch to another tab, when you go back and what else you draw, undo will undo on the previous 2 actions, the last one before the switch and the last one after.

4. This is not my bug, the problem is with webui automatic1111. When the browser scale is more or less than 100%, Sketch and Inpaint Sketch break if you send an image to them via buttons. Change the browser scale to 100% and everything will be fine.

# RU

Расширение [stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui).

Добавляет возможность зума в Inpaint, Sketch и Inpaint Sketch и горячие клавиши для удобства в работе.

Вы можете редактировать горячие клавиши по своему усмотрению, для этого нужно попасть в контекстное меню, нужно **щелкнув правой кнопкой мыши** в **Inpaint , Sketch и Inpaint Sketch, на области изображения**, и откроется контекстное меню, где вы можете настроить горячие клавиши по своему усмотрению.

Горячие клавиши работают только в области изображения, мышка должна быть на этой области , за исключением горячей клавиши для перемещения

Горячие клавиши по умолчанию:

**Shift + левая кнопка или колесо (удерживать)** - Переместить холст

**F (удерживать)** - Перемещение холста

**Shift + колесо** - Масштабировать холст

**Shift + "+" или Shift + "-"** - масштабирование холста (клавиши нумпада также работают)

**Ctr + колесо** - Изменить размер кисти

**S** - Максимально увеличить холст так, чтобы он поместился на экране

**R** - Сброс зума.

**Q** - Открыть/Закрыть выбор цвета

**T** - Открыть выбор цвета прямо над мышкой. Мышка должна быть в области изображения

**O** - Перекрыть все элементы и обратно

**Ctr-Z** - Отменить последнее действие

**C** - Переключение режима прозрачности маски ( Работает только в Inpaint )

**V** - Переключить режим прозрачности кисти ( Работает только в Inpaint )

В режиме прозрачности нельзя рисовать, иначе есть шанс что одна из линий отменится. Отключайте режим прозрачности маски когда рисуете. Данный режим пока работает не стабильно, введется работа по улучшению.

**Фичи**

1. Вы можете закрепить цветовую панель где угодно, для этого наведите мышкой на нужно место и нажмите "T" после чего каждый раз на "Q" Цветовая панель будет открываться в этом месте. Если вы нажмете на кнопку в правом углу, то панель сбросится и будет работать, как и должна.

2. Если вы увеличите картинку с большой шириной, которая не помещается в окно, то при нажатии на "S" вы получите увеличенную во весь экран картинку в полную ширину без полосы прокрутки

**Известные баги:**

1. Если постоянно переключать Sketch, Inpaint, Inpaint Sketch на разных уровнях зума через нижние кнопки, то картинка может обрезаться. Что бы решить эту проблему просто удалите картинку через крестик и снова перекиньте через кнопки или вручную.

2. Это не мой баг, проблема связана с webui automatic1111. Если вы отправляете картинку в Sketch или Inpaint Sketch через кнопки, то ломается отмена последнего действия на горячую клавишу и на кнопку. Что избежать этой проблемы: вы можете загрузить картинку напрямую, перетащить её из результата или через копирование и вставку.

3. Это не мой баг, проблема связана с webui automatic1111. Если вы что-то нарисовали в Sketch, Inpaint, Inpaint Sketch, а потом переключили на другую вкладку, когда вы вернетесь, и что ещё нарисуете, то отмена будет отменять по предыдущих 2 действия, последнее до переключения и последнее после.

4. Это не мой баг, проблема связана с webui automatic1111. При масштабе браузера больше или меньше 100%, Sketch и Inpaint Sketch ломаются, если отправить на них изображение через кнопки. Измените масштабе браузера до 100% и все будет отлично.
