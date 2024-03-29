




```
r language BS12, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis beyin, hepatoblastom metastazı TR, echo = (language == "TR")
## BS12 - beyin, hepatoblastom metastazı {#sec-BS12 }
```


```
asis brain, metastatic hepatoblastoma EN, echo = (language == "EN")
## BS12 - brain, metastatic hepatoblastoma {#sec-BS12 }
```






```
r BS12 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS12-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS12/HE.html",
  file = "./screenshots/BS12-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link







```
asis, echo = (language == "TR")

**beyin, hepatoblastom metastazı**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS12-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS12/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS12/HE.html)
```

```
asis, echo = (language == "EN")

**brain, metastatic hepatoblastoma**

[![Click for Full Screen WSI](./screenshots/BS12-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS12/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS12/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS12/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS12/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

beyin, hepatoblastom metastazı

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

brain, metastatic hepatoblastoma

:::

```









:::::










