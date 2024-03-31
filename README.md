# Nodejs - Windows 7+ backport
## Finally, windows 7 holdouts like you and me can enjoy nodejs on this "obsolete" and "obscure" operating system..!
![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/fcd071b1-6588-4a52-9f84-292a3d23e626)

Backporting:

**The backporting process is kinda complicated, if you're experienced enough I'll teach you how to do it on my discord: https://discord.gg/MnfHDJMqX5**

Installation:

Step 1: Download your prefered build from this repository, I'll download nodejs 21 for this tutorial
![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/1a66f42d-ab48-4e75-921b-edcea289c5a6)

Step 2: Extract node32 into C: (CRUCIAL STEP!)
![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/e3c4b385-08f9-4c60-bd7d-a4ada6554879)

Step 3: Test if it works (for good measure)
![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/82bd6dc4-6cb2-4343-9e3d-cb5ea8a657aa)

Step 4: Go into control panel, navigate to "System"

![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/e6301e21-ac8a-4ca8-a7dc-8b59ab017c26)

Step 5: Go into "System Protection"
![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/4ce5224e-b9e7-469d-a9e3-3229cb71b7c2)

Step 6: After that, go into "Enviorment Variables"
![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/e970f8d3-e4a4-45ea-845e-4221a85fb9eb)

Step 7: Do what I did in the screenshot
![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/ed7e2700-e478-4c3c-a35a-e0ea94f1648b)
**For copy pasting:**

User variables:

Path, c:\node32

System variables:

NODE_SKIP_PLATFORM_CHECK, 1

NODE_PATH, c:\node32\node_modules
