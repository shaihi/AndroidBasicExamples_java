# AndroidBasicExamples_java
A repo that has links to repos with Java code examples of Android projects.
All projects work and compile under Android Hedgehog with API level 30 and above.

## List breakdown
- [Notes SQL](https://github.com/shaihi/Notes_app_sqlite/tree/1a859cee9950cf84bcafbd4129dbf60d4b010649): A simple notes app that uses RecycleView to show the contact and SQLite to store it. The delete functionality is not implemented.
- [Menu Example](https://github.com/shaihi/menus_example/tree/6560bac33a0db296c990171be470d1cac74747b0): A very basic menu example with Navigation menu and context menu.
- [Recycle View](https://github.com/shaihi/RecycleViewExtensiveExample/tree/0a0df8cb367f841fe810ad6d162b077a5d1d4f6c): An app with a fully implemented RecycleView that loads content from static resources in the application. Includes itemClick events.
- [Thread example](https://github.com/shaihi/Threads_download_example/tree/5d26911196299255acf6a0f289e234642cd3dc80): An app that shows how to spin a thread to download a large file in the background without blocking the UI
- [MediaStore example](https://github.com/shaihi/MediaStore_LoadImage/tree/8e1a0f4ecfea6b50d157d186ebd07a560656e841): An app that uses the Android built-in activity for loading images from the gallery without additional permissions required.
- [Fragment example](https://github.com/shaihi/Fragment_Class_Example/tree/ae1f48e2ff0471ff0efc8aec151399f7900ec4b6): A simple example of switching between 2 fragments and passing info between them using an Arguments Bundle.
- [Maps fragment example](https://github.com/shaihi/Maps_Fragment_Example/tree/a3ad0ceb8f4595bc02786e208588aa48dac99e23): Showing how to place a pin on a map using OpenStreetMaps SDK. It also inlcudes a function to convert an address to longtitude and latitude.
- [Another fragment example](https://github.com/shaihi/Fragment_Example/tree/8038d8c7fc37dfacb7269057839c694bc537cdfe): This time passing info between fragments using a SQLite DB
- [Camera example](https://github.com/shaihi/Camera_MediaStore/tree/708051afd63428b43cabe37b898ce8a052b73d9f): an incomplete example of previewing using CameraX and capturing an image.
- [OpenAI GPT simple example](https://github.com/shaihi/gpt_example/tree/2926360011718240842b4eaf6374bcfc3a1165a4): You need to adjust the setup prompt and your OpenAI API KEY in strings.xml
- [BroadcastReceiver example](https://github.com/shaihi/BroadcastExample/tree/d6e1adf8ede8601b0253d506aaa0c1adc3ba969d): an example to get notified of battery level status.
- [Service example - running music in background](https://github.com/shaihi/ServiceExample/tree/7702d01f98a7108c60ce5353c5a32c0a5936d69c): This example also pushes notifications, but you can focus on the service part only
- [ContentProvider Example](https://github.com/shaihi/ContentProviderExample/tree/ac209e5a4724751d166f895d5328985d734c405e): An example using the contacts content provider. It does not show how to identify as a content provider and makes some use of reading and writing contacts through the provider.
- [Dialogs example](https://github.com/shaihi/DialogExample/tree/c9540d9939277ff3a9ca39a2863c5dd58db7606a): An example for dialog usage. Alert dialog has the option of default usage as well as multiple selection options. The progress dialog uses the up to date approach of AlertFialog with diplaying progress and there are also Date/Time dialogs.
- [ImageTextExtract](https://github.com/shaihi/ImageToTextExample/tree/c271c9d014fc41306294a8f8c529c727ae6f45ca): An example of using MLKit to extract text from an image loaded from the photo library. Pay close attention to the app level gradle and copy dependencies exactly as is. This app support API 34 without backward compatability.
- [Countdown example with custom view](https://github.com/shaihi/CountdownExampleWithRoundedDrwanButton/tree/43301ee2e8777890e527cacac15557da6ff71bcb): An example for a countdown timer in which the user inputs the time to count in seconds. The counter displays a growing circle to depict how much was covered.
