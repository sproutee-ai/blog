---
title: 開發上提升服務效能的方式
author: shwang6k
tags:
---

# 避免過多的 IO 操作，將 IO 操作的邏輯重新編排
# 記憶體預先載入，避免重複要求新的記憶體空間
# 留意 kernel mode 操作，避免過多的 system call

