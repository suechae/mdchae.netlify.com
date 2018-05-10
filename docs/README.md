# Sue: CV

Scholar : https://scholar.google.co.kr/citations?user=J2bg_TAAAAAJ&hl=en

## 논문 링크

- INI: <https://www.ncbi.nlm.nih.gov/pubmed/23245672>
- Insulin resistance: <https://link.springer.com/article/10.1007/s13410-012-0069-z>

```{r bib, include = FALSE, eval = FALSE}
library("knitcitations") 
knitcitations::cleanbib()
options("citation_format" = "pandoc")

citep('10.3349/ymj.2016.57.6.1468') #PR
citep('10.1016/j.humpath.2012.08.014') #NIH
citep('10.1007/s13410-012-0069-z') # 정동욱

knitcitations::write.bibtex(file="suechae.bib")
```
