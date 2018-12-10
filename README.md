# voice-assistant
voice assistant based on Mycroft.AI

### Installation Steps

```
cd ~/
git clone https://github.com/MycroftAI/mycroft-core.git
cd mycroft-core
bash dev_setup.sh
```

#### Starting Mycroft first time

__Start Services and CLI interface__

```
./start-mycroft.sh all
./start-mycroft.sh cli
```
__Pairing Mycroft for Linux__

- Once successfully installed, you will need to pair your Mycroft for Linux Device.
- Create account on https://home.mycroft.ai 
- On CLI Interface

Speak

    Hey Mycroft, pair my device

Mycroft will Speak
"I am connected to the internet and need to be paired. Your 6-digit Registration Code is XXXXXX"

-Use the Registration Code to pair your Mycroft for Linux Device with home.mycroft.ai.

- View the home.mycroft.ai documentation to learn how to add your Device to home.mycroft.ai.

- Once paired, you can then use basic Skills.

### Complete Docuemntation
https://mycroft.ai/documentation/linux/
