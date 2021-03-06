---
description: >-
  General settings — is a screen, where you can set up the most common behavior
  of the whole Quantower application.
---

# General settings

General settings — is a screen, where you can set up the most common behavior of the whole Quantower application. 

![General Settings are placed on the platform&apos;s main toolbar \(Gear Icon\)](../.gitbook/assets/launch-general-settings.png)

It is logically grouped into several tabs: 

* [**General**](general-settings-1.md#general)\*\*\*\*
* \*\*\*\*[**Control Center**](general-settings-1.md#control-center)\*\*\*\*
* \*\*\*\*[**Sounds**](general-settings-1.md#sounds)\*\*\*\*
* \*\*\*\*[**Confirmations & Warnings**](general-settings-1.md#confirmations)\*\*\*\*
* \*\*\*\*[**Time zone settings**](general-settings-1.md#time-zones)\*\*\*\*
* \*\*\*\*[**Excel RTD**](../miscellaneous-panels/excel-rtd-trading/)\*\*\*\*
* \*\*\*\*[**Messengers**](general-settings-1.md#messengers)\*\*\*\*

{% hint style="info" %}
The most settings are applied automatically, once you change them, but, in some cases, you will be prompted to confirm the changes apply; this action is required for complex settings, where the one change will influence a complex logic.
{% endhint %}

## General settings tab

![General settings of Quantower &#x2014; Localization, Themes, Sounds, RTD, Time zones](../.gitbook/assets/general-settings.png)

**Theme** — Сhoose one of the 8 color schemes that suits you best

* Default Blue theme
* Dark Autumn
* Dark Forest
* Dark Gold
* Grayscale
* Light Forest
* Light Gold
* Light Water

**Language \(beta\)** — Quantower supports 17 languages. In case of errors or inaccuracies in translation, any user can make changes to the text. Read the manual [how to make changes in selected language](https://help.quantower.com/customization/localization).

**Autosave settings \(every 5 minutes\)** — Quantower will save all changes of application settings in "Settings" folder and overwrite them every 5 minutes while the application is active. It also saves on application close.

**Abbreviate volume & ticks** — this option displays the volume values or the number of ticks in a simplified form \(1K = 1 000; 10K = 10 000 etc.\)

![Abbreviative Volume &amp; Number of Ticks](../.gitbook/assets/abbreviative-volume.png)

**Abbreviate crypto prices** — this option displays the abbreviated values of cryptocurrencies prices that have a large number of zeros.

![](../.gitbook/assets/abbreviate-cryptos.gif)

## Control Center

Control center is the starting point of all terminal, used as a launcher and informer simultaneously. And for optimal use of the space on it, we have added the ability to display/hide some controls.

![Configure the display of controls on the main control panel](../.gitbook/assets/general-settings-_-control-center.png)

## Sounds

Sounds are a good way of additional interaction with user allowing to inform about some activities even you don’t currently in front of your PC. Sounds can be enabled or disabled per certain action.

![](../.gitbook/assets/general-settings-_-sounds.gif)

**Enable sounds** — activates or disables all of the application sounds globally

The group of actions in Quantower, when the sound should be played consists of the most vital situations in application usage. This list is not final and can be extended or changed later. Each option has a set of controls: 

* enable/disable checkbox
* action name
* sound path \(you can select your custom path to any **.wav** file\)
* prelisten button \(play/stop\)

## Confirmations

![Confirmations and Warnings management](../.gitbook/assets/general-settings-_-order-confirmations.png)

| **Confirm order placement** | true | Ask before placing order |
| :--- | :--- | :--- |
| **Confirm order cancellation** | true | Ask before cancelling order |
| **Confirm order/position modification** | true | Ask before order of position modifications apply |
| **Confirm position reversing** | true | Ask before reversing the position |
| **Confirm application close** | true | Ask before closing the Quantower terminal |
| **Confirm bind close** | true | Ask before closing the binds |
| **Show deal tickets** | true | Show the pop-up screens with the trading notification |
| **Confirm hot button action** | true | Ask before make any action with Hot Button |

## Time zones

In case you are trading in various markets that are in different time zones, you will find it useful to switch the time indicator in [**Control center**](main-toolbar.md) to one of your favorite market times.

In Time zone settings group you can select what time zones are your favorite and should be displayed in a pop-up screen when you click the [**Time**](main-toolbar.md#time-and-time-zones) in **Control center**. Once you select several items from this list, you will then be able to switch between them easily.

![Favorite time zones management](../.gitbook/assets/time-zones.png)

## Excel RTD

Start from the version 1.39 Quantower supports RealTimeData \(RTD\) for sending data and other market information to Microsoft Excel®. Read our guide about [how to enable and use RTD function with Quantower](../miscellaneous-panels/excel-rtd-trading/).

![](../.gitbook/assets/general-settings-_-rtd.png)

## Messengers

Quantower Alert Bot will send a message to your Telegram account about all events that you set in the platform. For example, set a price alert on the chart, and when the price will reach this level, a notification to the messenger will be sent.

![](../.gitbook/assets/telegram-alerts.gif)

To add a bot to the Telegram, open the platform's **General Settings -&gt; Messengers -&gt; Duplicate alerts to Telegram**.

Specify your personal chat ID, which you can find out by clicking on the **Get ID** button. A new Chat ID Echo bot will open and it will show _**"Your Telegram Chat ID is: xxxxxxx"**_  
Enter your chat ID in the corresponding field and then connect to the Quantower Alert Bot.

![](../.gitbook/assets/general-settings-_-messengers.png)

