---
    layout: post
    title: test试试水看
---
# 开始写博客
## 先写个shader的看看
### 截图
assets/20220711/SG001.png
### 插入链接
[我找了个b站视频](https://www.bilibili.com/video/BV1A3411w765?share_source=copy_web)
### 敲一段代码看看
` tags "Queue" = "opaque" "TenderType" = "Geometry" `
### 敲个代码块看看
```
    {
        Shader "JLong/vfex/addnoise"
        {
            properties{
                _MainTex = ("_MainTex",2D) = []"white"
            }
            
            SubShader{
                tags{
                    "Queue" = "Transparent"
                }

                pass{
                    CGPROGMA
                    ENDCG
                }
            }
        }
    }
```
