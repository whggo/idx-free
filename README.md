
---

# 部署脚本优化：自动获取 UUID

本修改基于 **[eooce 老王](https://github.com/eooce)** 提供的部署脚本，核心改进在于**实现了 UUID 的自动化生成**，无需手动填写。这提高了脚本的便利性和通用性，尤其适用于批量部署或不希望硬编码 UUID 的场景。

---
## 运行命令
```
wget https://raw.githubusercontent.com/whggo/idx-free/refs/heads/main/install.sh
bash install.sh
```
## 或者
```
curl -sSL https://raw.githubusercontent.com/whggo/idx-free/refs/heads/main/install.sh | sh
```
## vps或者软路由安装火狐
```
bash <(curl -l -s https://raw.githubusercontent.com/byJoey/idx-free/refs/heads/main/Firefox.sh)
```
## 核心改动说明

原脚本中，UUID 需要手动指定一个固定的值，例如：

```bash
export UUID="9afd1229-b893-40c1-84dd-51e7ce204913" # uuid，
```



## 感谢

再次感谢 **eooce 老王** 提供的优秀脚本作为基础，使得本次功能优化成为可能。这个优化使得部署过程更加自动化和灵活，，提升了用户体验。
