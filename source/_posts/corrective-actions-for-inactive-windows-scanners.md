---
title: Corrective Actions for Inactive Windows Scanners
date: 2025-01-11T17:56:43.287Z
updated: 2025-01-12T18:26:06.361Z
tags:
  - win11
  - win10
  - win7
categories:
  - ScannerIssues
description: This Article Describes Corrective Actions for Inactive Windows Scanners
excerpt: This Article Describes Corrective Actions for Inactive Windows Scanners
thumbnail: https://thmb.techidaily.com/54da0f4f94eef8925e725ad6e5d476f72d3b4dfe3f3f6a2e608d839212aa9eeb.jpg
---

## How to Fix HP Scanner Not Working - 2022 Tips

![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd167112d84d.jpg)

 If your**HP scanner is not working** , don’t worry. This is a common scanner problem and you can fix it quickly and easily.

## Why is my HP scanner not working?

 The HP scanner not working issues include**the** scanner won’t scan, the scanner not being detected by your computer, or errors popping**up** when you’re using your scanner, etc.

 The causes for these problems are various and sometimes hard to identify. As you can imagine, the connection problem can prevent your scanner from connecting to the computer, and the software and services problems in your computer are the possible reasons for this issue.

 But don’t worry. We’ll help you fix the scanner not working on HP.

## How to fix the HP scanner not working

 Here are solutions that have helped people resolve the same issue. You don’t need to try them all; just work your way down the list.

1. [**Check the connection issue**](#F1)
2. [**Enable Windows Image Acquisition (WIA) service and associated services**](#F2)
3. **[Update your scanner driver](#F3)**
4. [**Troubleshoot hardware problems**](#F4)
5. [**Run System File Checker**](#F5)

 The screenshots below come from Windows 10, and fixes apply to Windows11.

---

### Fix 1: Check the connection issue

 To use your scanner, you need to make sure that your scanner is**powered on** in the first place.

 Then you should check the**connection** **issue** . If you’re using a USB scanner, check the**USB ports** and**USB cables** to ensure it works properly. While you’re using a network scanner, ensure your computer has a good**Internet** **connection** , and your scanner connects to your computer under the Internet. In addition, if you’re using **[VPN](https://tools.techidaily.com/drivereasy/download/)**  on your computer, try**disconnecting VPN** from your computer and scanning again.

 If you’ve checked the above steps and your HP scanner still doesn’t work, don’t worry. There is something else to try.

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Fix 2: Enable Windows Image Acquisition (WIA) service and associated services

**Windows Image Acquisition** **(WIA)** is a Microsoft model that allows graphics software to communicate with imaging hardware such as scanners and cameras. So you should enable WIA service in your computer if your scanner stops working. Here’s what you need to do:

1. On your keyboard, press the**Windows logo key** and**R** at the same time to invoke the**Run** box.
2. Type**services.msc** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1678201865.jpg)
3. Scroll down and double click**Windows Image Acquisition (WIA)** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd167eed749a.jpg)
4. In the popup pane, ensure the**Startup type** is set**Automatic** , and the**Service status** is**Running** .  

![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd168549db26.jpg)  
 If the**Service status** is already**Running** , click**Stop** to stop the service, then click**Start** to re-enable the service.

5. Click**Apply** and**OK** to save the changes.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1688e0055e.jpg)

 Then restart your computer. Try to use your HP scanner again and see if it works now.

 If your HP scanner issue still persists, follow these steps to enable some more services:

1. On your keyboard, press the**Windows logo key** and**R** at the same time to invoke the Run box.
2. Type**services.msc** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1678201865.jpg)
3. Ensure these services are set to**Automatic** and the**Service status** is**Running** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

   * **Remote Procedure Call RPC**  
   * **DCOM Server Process Launcher**  
   * **RPC Endpoint Mapper**  
   * **Shell Hardware Detection**  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd169897b1a1.jpg)  
   **INFORMATION:**  

    The**Windows Image Acquisition (WIA)** service is dependent upon the**Shell Hardware Detection Service** , while the**Shell Hardware Detection Service** is dependent upon these services: Remote Procedure Call RPC, DCOM Server Process Launcher, and RPC Endpoint Mapper.
4. Save the changes and try your scanner again to see if it works.

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Fix 3: Update your scanner driver (Windows PC)

 A missing or outdated scanner driver can cause your HP scanner not to work, so you should update your scanner driver up to date.

 There are two ways to update your scanner driver:**manually** and**automatically** .

**Manually update scanner driver** – You can go to the website of your scanner manufacturer, find the latest driver for your scanner, and install it on your computer. This requires time and computer skills.

**Automatically update scanner driver** – If you don’t have time or patience, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can download and install your drivers by using either the Free or Pro version of Driver Easy. But with the Pro version, it takes only 2 clicks (and you get full support and a**30-day money-back guarantee** ):

1. [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click**Scan Now** . Driver Easy will then scan your computer and detect any problem drivers.  

![](https://images.drivereasy.com/wp-content/uploads/2023/03/Driver-Easy-download-needed.jpg)
3. Click the Update button next to your scanner to download the latest driver (you can do this with the FREE version), then install it on your computer.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Or click**Update All** to automatically download and install all problem drivers in your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click**Update All** ).  

![](https://images.drivereasy.com/wp-content/uploads/2023/03/update-dell-touchpad-driver.jpg.png)

**The Pro version of Driver Easy** comes with full technical support.  
 If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://bellelily.pxf.io/m5azgm) .**

4) Restart your computer to take effect.

Then try scanning with your scanner to see if it works.

---

### Fix 4: Troubleshoot hardware problems

 It’s possible that there’s something wrong with your scanner, so run a troubleshooter in your computer to fix the issue.

1. Type**cmd** in the Windows Search bar and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/cmd-run-as-admin.jpg)
2. Copy & paste the following command line into the Command Prompt window and press**Enter** .  

`**msdt.exe -id DeviceDiagnostic**`
3. Click**Next** in the popped-up window and the troubleshooter will start detecting hardware problems automatically.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/next-step.jpg)
4. Follow the on-screen instructions to finish the troubleshooting and fix the detected issue.

 After that, try your scanner again and see if it’s working properly.

---

### Fix 5: Run System File Checker

 System File Checker (SFC) is a built-in Windows feature that scans corrupted system files and repairs it automatically.

 Your HP scanning is not working because of some corrupted system files, so you can try SFC to fix the problem.

1. Type**cmd** in the search box, right-click Command Prompt, and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd0319454560.jpg)
2. In Command Prompt, type the following command, then press**Enter** .  

sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd031d993e59.jpg)
3. Then wait for**Verification 100% complete** . This can take a while.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Once complete, Type**exit** in Command Prompt and press**Enter** to close the window.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd036dad46be.jpg)

Restart your computer and see if your scanner begins to work.

 However, sometimes the System File Checker may fail to detect critical or even some minor issues. If running the tool didn’t give you any luck, you should use a more powerful tool such as **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  , a more powerful tool that scans your computer for invalid registry issues, fragmented files, and Windows tweaks.

To fix your issues, follow the steps below to run a full scan of your PC:

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and it will run a free scan of your PC. Upon completion of the scan, the software will conduct a diagnosis and show you a summary of system issues. This will take a few minutes.
3. If Fortect detects any issues on your PC, click **Start Repair** to start the repair process.  

![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The repair is available with the paid version of Fortect which comes with full technical support. If you encounter any issues when using Fortect, feel free to contact their support team.

---

 So there you have it – Five effective methods to fix the**HP scanner not working** . Hope this post comes in handy and resolves your problem.

* [scanner](https://store.drivereasy.com/order/cart.php?PRODS=4731822&QTY=1&AFFILIATE=108875)
* [Windows](https://tools.techidaily.com/drivereasy/download/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-lessons.techidaily.com/new-best-android-videography-6-must-try-music-videos-apps/"><u>[New] Best Android Videography 6 Must-Try Music Videos Apps</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-next-gen-online-meeting-apps-azoom-no-more-for-2024/"><u>[Updated] Next-Gen Online Meeting Apps Azoom No More for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/4-ways-to-unlock-apple-iphone-6s-to-use-usb-accessories-without-passcode-by-drfone-ios/"><u>4 Ways to Unlock Apple iPhone 6s to Use USB Accessories Without Passcode</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/209842378-9780994072535-el-proposito-viaje-emocional-de-tu-alma/"><u>El propósito: Viaje emocional de tu alma | Free Book</u></a></li>
<li><a href="https://discover-bits.techidaily.com/expert-tips-from-yl-computing-secreting-data-invisible-to-others-in-windows-11/"><u>Expert Tips From YL Computing: Secreting Data Invisible to Others in Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-honor-90-lite-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Honor 90 Lite Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-turn-off-find-my-iphone-13-mini-when-phone-is-broken-by-drfone-ios/"><u>How to Turn Off Find My iPhone 13 mini when Phone is Broken?</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-boost-your-contents-reach-with-these-tiktok-unboxing-strategies/"><u>In 2024, Boost Your Content’s Reach with These TikTok Unboxing Strategies</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-in-depth-look-top-10-social-media-video-tools/"><u>In 2024, In-Depth Look Top 10 Social Media Video Tools</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-reset-itunes-backup-password-of-iphone-12-prevention-and-solution-by-drfone-ios/"><u>In 2024, Reset iTunes Backup Password Of iPhone 12 Prevention & Solution</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-the-best-methods-to-unlock-the-iphone-locked-to-owner-for-iphone-11-by-drfone-ios/"><u>In 2024, The Best Methods to Unlock the iPhone Locked to Owner for iPhone 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-bluetooth-connection-errors-for-paired-devices-not-communicating/"><u>Resolving Windows 11 Bluetooth Connection Errors for Paired Devices Not Communicating</u></a></li>
<li><a href="https://win-blog.techidaily.com/ultimate-guide-to-fixing-your-mouse-troubles-while-playing-resident-evil-village/"><u>Ultimate Guide to Fixing Your Mouse Troubles While Playing Resident Evil Village</u></a></li>
</ul></div>

