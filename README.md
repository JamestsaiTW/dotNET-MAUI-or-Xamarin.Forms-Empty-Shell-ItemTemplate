# .NET MAUI / Xamarin.Forms Empty Shell ItemTemplate (for Visual Studio)

This is a .NET MAUI / Xamarin.Forms "Empty Shell" ItemTemplate (for Visual Studio). It will help you create an empty Shell file in your .NET MAUI / Xamarin.Forms project easier.  
 
這是 .NET MAUI / Xamarin.Forms 的 "空白 Shell" 的 Visual Studio 項目樣板。會協助你在現有的 .NET MAUI / Xamarin.Forms 專案當中更輕易地建立空白的 Shell 檔案。  

## How to Setup?

### Visual Studio 2022
Copy **Xamarin.Forms Shell Empty Template.zip** file to `%USERPROFILE%\Documents\Visual Studio 2019\Templates\ItemTemplates\C#` folder.  
 
將此 **Xamarin.Forms Shell 的空白樣板.zip** 檔案複製到 `%USERPROFILE%\Documents\Visual Studio 2019\Templates\ItemTemplates\C#` 資料夾中。  

#### if you want to use .NET MAUI, please check you had install .NET MAUI workload in Visual Studio 2022 / 如果你要使用 .NET MAUI, 請確定你已經在 Visual Studio 中安裝 .NET MAUI 的工作負載

Please, blowse to `%USERPROFILE%\Documents\Visual Studio 2019\Templates\ItemTemplates\C#` folder. Create two folders, one named `.NET MAUI` another one named `Xamarin.Forms`.

Copy **.NET MAUI Shell Empty Template.zip** file to `%USERPROFILE%\Documents\Visual Studio 2019\Templates\ItemTemplates\C#\.NET MAUI` folder.  
Copy **Xamarin.Forms Shell Empty Template.zip** file to `%USERPROFILE%\Documents\Visual Studio 2019\Templates\ItemTemplates\C#\Xamarin.Forms` folder.  
  

請先到 `%USERPROFILE%\Documents\Visual Studio 2019\Templates\ItemTemplates\C#` 資料夾中，建立名稱為 `.NET MAUI` 資料夾與 `Xamarin.Forms` 資料夾。 

將 **.NET MAUI 的 Shell 空白樣板** 檔案複製到 `%USERPROFILE%\Documents\Visual Studio 2022\Templates\ItemTemplates\C#\.NET MAUI` 資料夾中。  
將 **Xamarin.Forms Shell 的空白樣板.zip** 檔案複製到 `%USERPROFILE%\Documents\Visual Studio 2022\Templates\ItemTemplates\C#\Xamarin.Forms` 資料夾中。  
  
### Visual Studio 2019
Copy **Xamarin.Forms Shell Empty Template.zip** file to `%USERPROFILE%\Documents\Visual Studio 2019\Templates\ItemTemplates\Visual C#` folder.  
 
將此 **Xamarin.Forms Shell 的空白樣板.zip** 檔案複製到 `%USERPROFILE%\Documents\Visual Studio 2019\Templates\ItemTemplates\Visual C#` 資料夾中。  

### Visual Studio 2017
Copy **Xamarin.Forms Shell Empty Template.zip** file to `%USERPROFILE%\Documents\Visual Studio 2017\Templates\ItemTemplates\Visual C#` folder.  
 
將 **Xamarin.Forms Shell 的空白樣板.zip** 檔案複製到 `%USERPROFILE%\Documents\Visual Studio 2017\Templates\ItemTemplates\Visual C#` 資料夾中。  

## How to use?

1. In your .NET MAUI or Xamarn.Forms project, select "Add" -> "New item...".  
 
   在你的 .NET MAUI 或 Xamarin.Forms 專案, 選擇 "加入" -> "新增項目..."。
   
2. Visual Studio 2022

   ### Only Xamarin.Forms

   Select "Empty Shell File" in "C# Items", edit your file name and click "Add".  
   ![English](/Screenshots/English%20for%20VS2022.png)

   選擇在 "C# 項目" 中的 "空白 Shell 檔案", 編輯 "名稱" 並且點選 "新增"。  
   ![繁體中文](/Screenshots/Traditional%20Chinese%20for%20VS2022.png)

   ### Both .NET MAUI and Xamarin.Forms

   #### For .NET MAUI
   Select ".NET MAUI Empty Shell (XAML)" in the ".NET MAUI" section of "C# Items", edit your file name and click "Add".  
   ![English](/Screenshots/English%20for%20.NET%20MAUI%20in%20VS2022.png)
   在 "C# 項目" 中找到 ".NET MAUI" 後，再選取 ".NET MAUI 空白 Shell (XAML)" 項目, 編輯 "名稱" 並且點選 "新增"。 
   ![繁體中文](/Screenshots/Traditional%20Chinese%20for%20.NET%20MAUI%20in%20VS2022.png)

   #### For Xamarin.Forms
   Select "Empty Shell File" in the "Xamarin.Forms" section of "C# Items", edit your file name and click "Add".  
   ![English](/Screenshots/English%20for%20Xamarin.Forms%20in%20VS2022.png)
   在 "C# 項目" 中找到 ".NET MAUI" 後，再選取 "空白 Shell 檔案", 編輯 "名稱" 並且點選 "新增"。
   ![繁體中文](/Screenshots/Traditional%20Chinese%20for%20Xamarin.Forms%20in%20VS2022.png)

   Visual Studio 2019 / 2017  

   Select "Empty Shell File" in "Visual C# Item", edit your file name and click "Add".  
   Visual Studio 2019 / 2017  
   ![English](/Screenshots/English%20for%20VS2017&2019.jpg)

   在 "Visual C# 項目" 中選取 "空白 Shell 檔案", 編輯 "名稱" 並且點選 "新增"。  
   ![繁體中文](/Screenshots/Traditional%20Chinese%20for%20VS2017&2019.jpg)

3. Check the `namespace` of Shell .xaml/.cs file which is same as Xamarin.Forms project.  
 
   檢查 Shell .xaml/.cs 檔案中的 `namespace` 是否與 Xamarin.Forms 專案一致。
