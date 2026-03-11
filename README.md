# README

## Capslock as Hyper (✱)

Personalized from - https://github.com/Vonng/Capslock

Features:

- Capslock is hyper when held and escape when tapped
- Hyper terminal - `✱a` is tmux prefix, `✱d` is ctrl+d, `✱c` is ctrl+c, etc.
- Hyper apps - launch apps with hyper+e/r/t/y/f/g (iterm, browser, chat, notes, mail, etc.)
- Hyper window - navigate desktops with hyper+1/2/3/4 etc.
- Hyper navigation - hyper+h/j/k/l moves the cursor
- and more (see [Vonng/Capslock](https://github.com/Vonng/Capslock) for more info

## Move to Kanata

In 2025 I wanted to begin using homerow mods to reduce strain on my thumbs. I was using my thumbs for a lot of modifier functions and it was causing a lot of pain. All my attempts to enable HRM in Karabiner failed and I found kanata. It's a great cross platform solution that allows me to have HRM and nearly identical implementation across machines and operating systems. Originally, I wanted to have something that worked well on my laptop since I have my corne keyboard when I'm at my desk, but need to use the built-in keyboard when in meetings which was occurring more and more frequently. Since migrating to kanata, I've stopped using my corne altogether due to the quality implementation of HRM on the built-in laptop keyboard. I'm still having trouble getting HRM to function with key repeat on the corne, and in fact I can no longer update the corne keymapping due to the git actions failing to build properly anymore and I don't have the time to fix it. At home, I have a moonlander that has basically the same functionality as the kanata implementation here though, so I'm fine at the moment.

Some things of note:

- kanata uses the karabiner driver under the hood, so it's good that karabiner was installed and the driver was approved in the system settings.
- because kanata uses the karabiner driver, I want to keep karabiner up-to-date, however.
- karabiner and kanata cannot both be active at the same time because they both subscribe to the driver, and whichever service subscribes first overrides the other.
- I use kanata in a tmux session. I don't want to make it into a system service for the sake of potentially having the process fault and break my ability to login or manage the machine.
