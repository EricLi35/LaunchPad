# LaunchPad

Question:
You and your friends are developing a new start-up called DRUBER, a drone-based ride share application that carries you to your destination. The original specification was to develop a web page that works in 1920x1080 however your company has realized that it is missing an entire market of smartphone users. Describe how you can modify your code to work in smartphone resolutions e.g. 750x1334 (iPhone 8). Please give specific examples where possible, but do not implement an entire DRUBER clone!

This task calls for the modification of screen size and orientation, from landscape on a webpage to portrait on a smarthpone. There are essentially two different types of apps - native and hybrid.

Native apps are built entirely from scratch, which results in higher levels of performance. Moreover, they also gain elevated access to the native capabilities of the device, such as GPS for example. However, native apps are very expensive and time-consuming to build, and most of the time, the extra work that comes with native apps are unnesscary. 

Hybrid apps on the other hand, allows one to convert the website into an app using purely web-based technologies. It is called a hybrid because it uses a native container which displays web information. Most importantly, it still maintains the same features and user experience of the desktop app.

When modifying the code, it is important to use similar milestones and checklists when first building the desktop app, and applying them to the mobile version. However, the design workflow should be tweaked to specifically accomodate for an app-based platofrom. Moreover, when transitioning to a mobile design and trying to make the website responsive, it is important to adhere to best practices. 

For example, it is important to set the correct viewport. The viewport tag in meta can provide the browser valuable information on how to control the page's dimensions and scaling. Typically, mobile browsers render the page at a width of desktops, but with increased font sizes and scaling the content to fit the screen.

When it comes to images, they have fixed dimensions and in the case where they are bigger than the viewport, scrollbars will appear. 
