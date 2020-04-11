# 思考题解答 {#solution}

## 桌面环境的选择 {#choice-of-desktop-environment}

!!! tips "提示"

	这是一个相对主观的问题，不同的人可能会给出完全不同的回答。可以尝试一下其他的桌面环境之后再想一想。

??? info "解答"

	在选择桌面环境的时候，用户可能会从以下几个方面去考虑：

	- 桌面环境需要多少系统资源？我们的虚拟机镜像选择 XUbuntu 的一个重要原因就是我们希望镜像能够在配置较低的电脑上也能流畅运行，而 Xfce 桌面环境是非常轻量级的。有些桌面环境，如 KDE 或者 GNOME，需要比较多的系统资源，在老旧的电脑上会非常卡顿。而与 Xfce 类似的轻量桌面环境还有 LXDE 等。
	- 桌面环境是否美观？当然不同的人对「美观」的要求也是不同的。在十余年前，曾经流行过通过 Compiz 为桌面环境添加绚丽的 3D 效果。如今，KDE 和 GNOME 也为用户提供了美观的界面。另外还有一些桌面环境专注于美观的用户界面，例如 Enlightenment (e17)。
	- 桌面环境是否可以充分自定义？不同的用户对桌面环境的要求不同，并且也会有不同的设置。例如，GNOME 通过拓展程序可以实现丰富的功能。
	- 桌面环境是否高效？追求效率的一个例子是，一部分用户会选择「平铺式窗口管理器」(Tiling window manager) 来管理窗口。在平铺式中，各个窗口不重叠，所有窗口合起来占满了整个屏幕。典型的平铺式窗口管理器有 i3, awesome 等。
	

## 桌面环境的使用场合 {#when-to-use-desktop}

??? info "解答"

	在 Linux 服务器的环境下，桌面环境不是必需品。我们知道，与 Windows 不同，Linux 下桌面环境也只是一个（可选的）软件。服务器中的配置完全可以在命令行中完成。

	并且，安装桌面环境会占用额外的资源，尤其对于性能较低的服务器（例如在各种云服务器厂商上可以购买到的配置最低的机器）。配置远程连接桌面（如使用 VNC）也是比较麻烦的。