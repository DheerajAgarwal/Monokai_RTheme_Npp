# What to Change and Where to change.

I am a regular user of Notepad++ and love the tool. I also use it regularly to write, understand or trouble shoot `R` scripts.
Even though Npp has support for the language, the syntax highlighting doesn't work when t=you change the default theme to anything dark like Monokai.

After seeking help from Google searches / SO and Npp forums, i finally decided the best bet is for me to code it myself. 

Here is the code changes and the steps for anyone needing to use it. 

### Step0:
Make a copy of the files just in case you want to revert back.


### Step1:

Navigate to `%APPDATA%\Notepad++` and find file **langs.xml**.  
Append the code from the repo file **langs.xml** to the notepad++ file **langs.xml**.

### Step2:

navigate to **themes** folder and locate **Monokai.xml**.
Apend the code from the repo file **Monokai.xml** to the notepad++ file **Monokai.xml**.

### Step3 (Optional):
You can play around the position in the original XMLs. The code position within the file will determine the position of the language theme in Npp preferences.


