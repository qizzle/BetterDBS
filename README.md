# BetterDBS
BetterDBS is a modified version of DBS. This includes a quick installer.
> Note: You still need a legally copy of [Discord Bot Studio](https://discordbotstudio.org/) to use BetterDBS.

# Installation

**Make sure that you have the asar package installed gloably**
> npm i -g asar

Simply download the latest release of **BDBS** in the "Release" tab and run the **.exe** file.
Now you just need to wait to installing it and it launches the installer.

In the launcher, you need to provide a path from your Discord Bot Studio installation.
Simply type the path or just click on the folder emoji and search in the explorer for your path.

It should look like this:

![image](https://user-images.githubusercontent.com/52245845/152658285-860d6834-4ed7-4b6f-a070-d4e978050d07.png)

Now you can click on the blue "Install" button.

After some waiting, you should see the button color changed to green and it says "Installed"

![image](https://user-images.githubusercontent.com/52245845/152658376-ef0464df-bedf-489c-ba1b-76a8560576b0.png)

Run Discord Bot Studio and you're ready for **BDBS**

# Themes
Themes are one of the core features of **BDBS**.
There're already two or more preinstalled themes (**light** & **dark**).

You can also import your own theme!
> Just make sure it's a Bootstrap **4** theme

## Installation of a new theme
In this example installation, we're gonna install the [**Darkster** Theme for **Bootstrap 4**](https://bootstrap.themes.guide/darkster/).

Firstly, download the theme as a .css file.
You're probally gonna get the same thing as in my screenshot:

![image](https://user-images.githubusercontent.com/52245845/152658750-264048dc-0ffc-4b82-9d7b-5d19a2970482.png)

Just copy the whole css code (**CTRL/STRG + A**; **CTRL/STRG + C**) and go inside Discord Bot Studio.
Go inside the **Settings** tab and press on "Open themes folder".
It opens your windows explorer.

![image](https://user-images.githubusercontent.com/52245845/152658841-f2857069-6e1b-4b48-bf8d-95b93039b193.png)

Create a new file and call it **darkster.css**. Simply edit the code with your favorite texteditor.
For this example i'm gonna use [Visual Studio Code](https://code.visualstudio.com/), but you can also use the default **Note** app.

In **Visual Studio Code** simply paste (**CTRL/STRG** + **V**) the theme source code.
It should look like this:

![image](https://user-images.githubusercontent.com/52245845/152658941-2cb31de9-a463-45f0-a8dc-84807ca23bad.png)

Now just save the file.

We're again getting inside the themes folder and creating a new file called **darkster.theme.json** and open it.
> Note: The .css and .theme.json files should have the same name for each theme.

In there we're creating a new json object.
```json
{

}
```

Now add following things:
```json
{
  "title": "YOUR THEME NAME",
  "description": "DESCRIPTION OF YOUR THEME",
  "author": "AUTHOR"
}
```

And simply replace the placeholders with our actually data.
```json
{
  "title": "Darkster",
  "description": "A dark background theme with bold contrasting colors.",
  "author": "Bootstrap 4 Themes"
}
```

Save the json file and reload Discord Bot Studio.
Go inside the "Settings" tab and if you did everything right, you should see a new theme.

![image](https://user-images.githubusercontent.com/52245845/152659150-91430028-2c2e-4fb4-95ff-d545a49725e4.png)

Simply click on it and have fun with your new theme.
