[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=0FF700&center=true&vCenter=true&width=600&height=100&lines=Linux+Aliases;nano+.bash_aliases;A+tutorial+for+beginners+by+a+beginner)](https://git.io/typing-svg)

[![UBUNTU - Aliases](https://img.shields.io/badge/UBUNTU-Aliases-E95420?logo=ubuntu&logoColor=ffffff)](https://)  [![Beginner - Guide](https://img.shields.io/badge/Beginner-Guide-99CC00?logo=readthedocs&logoColor=ffffff)](https://)  [![dev.to - Blog](https://img.shields.io/badge/dev.to-Blog-000000?logo=dev.to&logoColor=ffffff)](https://dev.to/kurtissfrost)  [![contributions - welcome](https://img.shields.io/badge/contributions-welcome-teal)]() 

---

Hello and welcome to my guide to creating aliases on Ubuntu. You can also find this on my [dev.to blog](https://dev.to/kurtissfrost/ubuntu-aliases-by-a-beginner-for-beginners-1g3n) by clicking the button above. Before we begin, let me just say that I am no linux guru. There is probably another way to do this that is better but, this was how I learned how to do it and I want to share my process. For all examples listed below, I am using Ubuntu 22.04 LTS. Now,let's jump right on in!

---

Ok, so first off, you need to find a command that you either want to change because of the length, or because you want to map it to a different input for either ease of memory or for style. For example, the command to put a linux machine to sleep "ststemctl suspend" That's kind of a length command. So let's change it to something both flashy and easier to remember like "goodnight"

---

1. Open your terminal up by either going to "show applications" or by using the keyboard shortcut ctrl+t.

2. In the terminal, type the following
> nano .bash_aliases

3. In your newly created file, type 
> alias goodnight='systemctl suspend'

4. For convenience. we should also add the following aliases (it will make sense later)
> alias CA='source .bash_aliases<br /><br />
>alias aliases='nano .bash_aliases 

5. Next, hit ctrl+x and then press Y. Once you do this, you can press enter and it will take you back to the terminal.<br /><br />

Unfortunately you can't just use your new shiny commands yet. You need to type 
>source .bash_aliases

Remember earlier when I said to add the alias CA? This is why. Now that we have that alias, instead of typing the nano command again, we can just type the word alias in the terminal to add more aliases. <br /><br />

---

Using this method, you are really only limited by your imagination.<br />

Hopefully this guide has been helpful and you can create your own unique and interesting aliases.
