# Yilmazturk Theme Selector
🇬🇧 Add dark mode and light mode to your app with this class.

🇹🇷 Uygulamanıza uğraşmadan koyu mod ve açık mod ekleyin. 

# 🇹🇷 Türkçe
* YilmazturkThemeSelectorTR dosyasını indir ve projenin içine at.
* Formunun ``Load`` fonksiyonunun içine
  ```csharp
    YilmazturkThemeSelector.Apply("açık", this);
  ```
  kodunu yaz. ``"açık"`` yazan yere temayı yaz. ``"koyu"`` yazarsan koyu mod, ``"sistem"`` yazarsan sisteme göre ve ``"sistemDeğişir"`` yazarsan kullanıcı temayı Windows ayarlarından değiştiğinde uygulamanında teması anında değişir.

# 🇬🇧 English
* Download YilmazturkThemeSelector file and move to your project.
* Add your form's ``Load`` void to
  ```csharp
    YilmazturkThemeSelector.Apply("light", this);
  ```
  code. Type the theme where it says ``"on"``. If you type ``"dark"``, the dark mode will be changed, if you type ``"system"`` it will change according to the system, and if you type ``"systemChange"``, when the user changes the theme from Windows settings, the theme of the application will change instantly.
  
