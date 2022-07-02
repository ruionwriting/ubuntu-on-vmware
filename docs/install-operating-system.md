# Install operating system

> At the end of this guide we'll have a fresh installation of Ubuntu. We'll take a snaphot and we'll be able to resume or redo our VM anytime from this point in time.

We start by powering up the newly created virtual machine. The Ubuntu install should load:

![image](https://user-images.githubusercontent.com/1220067/177011070-1485a120-aaff-49a9-bab4-f5e03db7daeb.png)

> **Note**
> From the previous screen and going forward is very possible that you'll see some different UI and wording as it varies across Ubuntu variants. Mostly I proceed with the examples to provide some guidance for most standard installations.

![image](https://user-images.githubusercontent.com/1220067/177011206-646bf93c-68d7-4c99-bbea-ee674992c228.png)

Now I choose to install Ubuntu. It starts with _Keyboard layout_ that I adjust to my current harware and/or preference:

> **Note**
> Ensure that you apply your own preferences to avoid friction down the road.

![image](https://user-images.githubusercontent.com/1220067/177011262-8397371e-5ee8-4ab2-9f34-bf94a74129fa.png)

Hit `Continue`. Now for _Updates and other software_:

![image](https://user-images.githubusercontent.com/1220067/177011362-5722abb6-3bb4-4aff-9b30-89590f6a6ed4.png)

I recommend the sellection presented here. Hit `Continue`.

![image](https://user-images.githubusercontent.com/1220067/177011394-8a504f04-842d-4d14-829e-feb13dfe6d33.png)

Hit `Install Now` and:

![image](https://user-images.githubusercontent.com/1220067/177011419-68d4d500-e45f-4233-9b7e-1f874f9754fb.png)

Hit `Continue`. Remaining options (_Timezone_, _User Info_ and _Install_) adjust according to your needs.

![image](https://user-images.githubusercontent.com/1220067/177012235-2de250f2-b5c5-4ed6-a99a-309e749f924a.png)

Hit `Restart Now`.

We are all done in regards to installing the operating system. Before we continue let's take a snaphot:

![image](https://user-images.githubusercontent.com/1220067/177012314-b7cd8d66-5bc9-401d-8f4c-1b2938ba5320.png)

Next we can set up and customise our Ubuntu installation.

> **Note**
> So far we've done the least interesting part of the setup because of so many manual actions. From this point forward I'll rellying more in automation assisted by scripts. Regarless I'll try to keep record of both ste-by-step instructions and script-based approach so that we can learn as well about the internals of the various configurations we make along the way.