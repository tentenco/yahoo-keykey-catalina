Since macOS 10.15 Catalina is no longer able to support 32 bits software installation, we also mistakenly thought that the "Yahoo! input method" is 32 bits. Fortunately, the station friends corrected it. In fact, the input method itself is 64 bits, but the installation program is 32 bits, so Can not be installed.

[![](https://i.imgur.com/X55LuTp.png)

## Can't install after upgrading Catalina?

If the Yahoo! input method is not installed before the upgrade, users will not be able to use it, and people who use the early installation package will not be able to install it directly in Catalina.

[![](https://s3.tenten.co/images/2020/06/b6c9dad95081b10ddd0f49af191e662a-thumb.jpg)](https://s3.tenten.co/images/2020/06/b6c9dad95081b10ddd0f49af191e662a-thumb.jpg)

![](https://s3.tenten.co/images/2020/06/f6393e36d7d0f7daa951c3a664b85205-thumb.jpg)

▲ From the system information, the installer of the input method is "old version software", but the input method itself is not the old version software.

![](https://s3.tenten.co/images/2020/06/08a3f44599fe525a431460e3900043cb-thumb.jpg)

▲ The software will be closed after the upgrade.

![](https://s3.tenten.co/images/2020/06/18efcc5f1bfe0ed8012149ec359d84c7-thumb.jpg)

▲ The system will show that it must be updated before it can be used.

## Catalina installs Yahoo! Qimo input method

1. Go to the setting "Security and Privacy" and change the "Allow Apps Downloaded from" below to "Any Source".
[![](https://s3.tenten.co/images/2020/06/065a604c69aa28b0951395caa6a8bd99-thumb.jpg)](https://s3.tenten.co/images/2020/06/065a604c69aa28b0951395caa6a8bd99-thumb.jpg)

2. If "any source" is not available, please enter the following command:
> `Sudo spctl --master-disable`

![yahooinput04](https://s3.tenten.co/images/2020/06/ebae27bf3fe17d5ced330646f8bed8ad-thumb.jpg)

3. Download the [Yahoo! input method]((https://github.com/zonble/ykk_installer/releases)) repackaged in 2018 
[![](https://s3.tenten.co/images/2020/06/a357593cf44b71382bd77800a29afccb-thumb.jpg)](https://s3.tenten.co/images/2020/06/a357593cf44b71382bd77800a29afccb-thumb.jpg)


4. After decompression, install with YahooKeyKey.pkg.
[![](https://s3.tenten.co/images/2020/06/5a203f53b3a25c2d21100181e0ef87fe-thumb.jpg)](https://s3.tenten.co/images/2020/06/5a203f53b3a25c2d21100181e0ef87fe-thumb.jpg)

5. Restart after completion.
[![](https://s3.tenten.co/images/2020/06/8a38d1f661f8632e729174ba15da757e-thumb.jpg)](https://s3.tenten.co/images/2020/06/8a38d1f661f8632e729174ba15da757e-thumb.jpg)

6. Enter "Keyboard" in "Settings", select the input mode and press "+".
[![](https://s3.tenten.co/images/2020/06/e52564a3fcb1d69b9e4af6cc22d0d36e-thumb.jpg)](https://s3.tenten.co/images/2020/06/e52564a3fcb1d69b9e4af6cc22d0d36e-thumb.jpg)

7. Just select "Yahoo! Qimo Input Method" in Traditional Chinese.
[![](https://s3.tenten.co/images/2020/06/b7075b6a7ffb840081a47d92a3431107-thumb.jpg)](https://s3.tenten.co/images/2020/06/b7075b6a7ffb840081a47d92a3431107-thumb.jpg)


8. Congrats! You've successfully used Yahoo input method on macOS!
[![](https://s3.tenten.co/images/2020/06/b2ee35af50a3af56df68b26ca13d0caf-thumb.jpg)](https://s3.tenten.co/images/2020/06/b2ee35af50a3af56df68b26ca13d0caf-thumb.jpg)


### Credit and Original repositories > [zonble](https://github.com/zonble)