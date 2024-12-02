+++
date = '2024-12-02T14:58:21+01:00'
draft = false
title = 'Mount DVD or CDs'
+++

Just mount the disk as it was an external drive:

```bash
mount /media/cdrom
```

after you are done, unmount like normal

```bash
umount /media/cdrom
```

> [!Note]
> If `cdrom` doesn't work try `cdrecorder` or `dvdrecorder`

[source](https://www.cyberciti.biz/faq/mounting-cdrom-in-linux/)