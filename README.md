# ColorPicker for Yii

The color picker widget is implemented based this jQuery plugin:
(see {@link https://github.com/laktek/really-simple-color-picker}).

This widget is more useful as a textfield (the default mode)

## Example:
```php
    ...
        $this->widget('ext.colorpicker.ColorPicker', array(
            'model' => $model,
            'attribute' => 'cor',
            'options' => array( // Optional
                'pickerDefault' => "ccc", // Configuration Object for JS
            ),
        ));
    ...
        $this->widget('ext.colorpicker.ColorPicker', array(
            'name' => 'cor',
        ));
    ...
```