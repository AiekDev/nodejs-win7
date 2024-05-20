# Nodejs - Windows 7+ backport
## Finally, windows 7 holdouts like you and me can enjoy nodejs on this "obsolete" and "obscure" operating system..!
![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/fcd071b1-6588-4a52-9f84-292a3d23e626)

### Backporting:

Will make the guide public soon, you need to also make sure everything works well in powershell, not only CMD.

### Installation:

Step 1: Download your prefered build from this repository, I'll download nodejs 21 for this tutorial
![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/1a66f42d-ab48-4e75-921b-edcea289c5a6)

Step 2: Extract node32 into C: (CRUCIAL STEP!)
![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/e3c4b385-08f9-4c60-bd7d-a4ada6554879)

Step 3: Go into control panel, navigate to "System"

![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/e6301e21-ac8a-4ca8-a7dc-8b59ab017c26)

Step 4: Go into "System Protection"
![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/4ce5224e-b9e7-469d-a9e3-3229cb71b7c2)

Step 5: After that, go into "Enviorment Variables"
![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/e970f8d3-e4a4-45ea-845e-4221a85fb9eb)

Step 6: Do what I did in the screenshot

![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/ed7e2700-e478-4c3c-a35a-e0ea94f1648b)

**For copy pasting:**

User variables:

Path, c:\node32

System variables:

NODE_SKIP_PLATFORM_CHECK, 1

NODE_PATH, c:\node32\node_modules


Step 7: Go into CMD, and test it out!

![image](https://github.com/AiekDev/nodejs-win7/assets/145149166/855094da-8901-4eba-8cb3-416046fb1bd8)

