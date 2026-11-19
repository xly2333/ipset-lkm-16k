# ipset-lkm-16k

GitHub Actions 交叉编译 android16-6.12 GKI **16K 页**变体的 ipset 内核模块（小米 K90 Pro Max 25102RKBEC 适配）。

产物：ip_set 全系列 + xt_set + xt_addrtype + ip6table_nat，加载时 CRC 表清零（TanakaLun/IPSET_LKM 同款跨内核技巧）。

触发：Actions → build-ipset-lkm-16k → Run workflow。产物在 run 的 artifact `ipset-lkm-16k`。
