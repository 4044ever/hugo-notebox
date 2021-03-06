# hugo-notebox
Note Boxes for Hugo using TailwindCSS

I got the idea from [martignoni/hugo-notice](https://github.com/martignoni/hugo-notice), but somehow the i18n method didn't work well on my Hugo site, so I simplified it a bit and don't use i18n.

You can use the format:

    {{< notebox warning >}}
    This is a warning!
    {{< /notebox >}}

    {{< notebox note >}}
    A note for you.
    {{< /notebox >}}

    {{< notebox tip >}}
    Just a tip.
    {{< /notebox >}}

    {{< notebox info >}}
    Some info for you
    {{< /notebox >}}  

    {{< notebox trivia >}}
    Funny note...
    {{< /notebox >}}
    
For German: (you can add more languages easily)
    
    {{< notebox warning.de >}}
    Das ist eine Warnung!
    {{< /notebox >}}

![image](https://user-images.githubusercontent.com/3244771/168051739-effe2bb7-7e85-417d-add8-27812950d7fe.png)


Precondition: You must have Hugo and TailwindCSS up and running.

Installation: Simply copy `notebox.html` into the `/layouts/shortcodes/` folder.
