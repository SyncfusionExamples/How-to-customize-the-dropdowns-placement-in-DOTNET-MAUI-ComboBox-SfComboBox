# How-to-customize-the-dropdowns-placement-in-DOTNET-MAUI-ComboBox-SfComboBox
This repository contains a sample demonstrating of customizing the dropdown's placement in .NET MAUI ComboBox
## DropdownPlacement support in .NET MAUI ComboBox (SfComboBox)
 We can change the dropdown's position in SfComboBox by changing the DropdownPlacement value.

The following code example illustrate how to set DropdownPlacement in SfComboBox.

**XAML**
```
<editors:SfComboBox  WidthRequest="200" 
                          HeightRequest = "40"
                          DropDownPlacement = "Auto">
                <editors:SfComboBox.ItemsSource>
                    <x:Array Type="{x:Type x:String}">
                        <x:String>Telegram</x:String>
                        <x:String>Televzr</x:String>
                        <x:String>Tik Tok</x:String>
                        <x:String>Tout</x:String>
                        <x:String>Tumblr</x:String>
                        <x:String>Twitter</x:String>
                    </x:Array>
                </editors:SfComboBox.ItemsSource>
            </editors:SfComboBox>

```