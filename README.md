# What is it

This code is an example of a Bot for WhatsApp Web.

I have created this piece of code just to know if it was viable. It is just a concept, just a test.

# How to use it?

1. Open `chrome`, then visit `web.whatsapp.com`
2. Press `F12`, click at `console`
3. Copy all the `bot.js` code and paste into console. Don't worry, you can trust me, I am a lovely person.

4. Installed!

5. Now ask your friend to send you this message: `@HELP`

# FAQ

#### So it's possible to create a Bot in WhatsApp Web?

Yes, it is.

#### Am I going to be banned?

Hum, so you already know that WhatsApp does not allow Bots, right?

Well, you're right: WhatsApp will ban you forever if they discover you are running a Bot long-term. For a small test: Don't worry, go forward.

I can't understand why Mark Zuckerberg still forbids Bots, he is the kind of guy who [loves to copy-cat](https://www.vox.com/2017/3/28/15079774/facebook-stories-snapchat-instagram-copy) all the good things on the Web, right?
 Why not simply copy WeChat features? If you go to China, you will discover that you can pay all your bills using WeChat, including silly things like P2P payments or restaurants. Paper money is past.

Elon Musk may be right, perhaps little Zuckerberg [is just being limited in this subject](https://twitter.com/elonmusk/status/889743782387761152), lol.

I can't guarantee that you are not getting banned in the long term using this Bot. I really don't think so, but I can't guarantee.

#### Bullshit! I got banned using yowsup!

Hold on mate, there are kids here.

First, [yowsup](https://github.com/tgalal/yowsup) is a great python library! Simply awesome.

But their problem is: They connect to WhatsApp servers directly, without any middleware. So it is not so hard for the WhatsApp team to create ban rules if you are using yowsup.

I got banned many times in the past, so I know, sooner or later, you will get banned as well. It's just a matter of time. You can see that I am probably right just looking [here](https://github.com/tgalal/yowsup/issues/1558),
[here](https://github.com/tgalal/yowsup/issues/1979),
[here](https://github.com/tgalal/yowsup/issues/1806) and
[here](https://github.com/tgalal/yowsup/issues/1686).

That's why I wrote this code. Using WhatsApp Web, it is almost impossible for the WhatsApp team to know that you are running a Bot.

#### But... What are the limitations?

A lot of limitations!

1. As you are handling the DOM directly, you can't process hundreds of messages at once. Yowsup is much better at this subject.

2. You can't start a message with an unknown person. You can only answer them, mainly because you can't add a new fellow to the Contacts list on WhatsApp Web.

3. You have to install WhatsApp on your phone, connect it to Wi-Fi and keep it charging all the time. So you have to have a cellphone exclusively for this Bot. You will need a computer with Chrome running as well. But that's the main objective: In order to avoid being detected as a Bot, you have to play this boring cat-and-mouse game.

#### I think there are some bugs in your code.

Yes, there were.

1. Your friend can't send `@HELP` followed by any other message really fast. This Bot only reads the last message. It's a bug (that can be fixed).

Feel free to fix and PR it. I will probably not touch this public repo anymore.

# -

Authors: [Bruno Kilian](https://github.com/bruno222) and [Nelson Galdeman](https://github.com/NelsonGaldeman)
