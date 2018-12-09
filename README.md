# Linux VPS一键屏蔽指定国家所有的IP访问
本脚本适用于`CentOS`、`Debian`、`Ubuntu`等常用系统。

使用`root`运行以下命令：

    wget https://raw.githubusercontent.com/iiiiiii1/Block-IPs-from-countries/master/block-ips.sh
    chmod +x block-ips.sh
    ./block-ips.sh
封禁`ip`时会要求你输入国家代码，代码查看：[点击进入][1]。记住所需输入的参数均为小写字母。比如`JAPAN (JP)`，我们就使用`jp`这个参数。

详细说明：https://www.moerats.com/archives/585/

  [1]: http://www.ipdeny.com/ipblocks
