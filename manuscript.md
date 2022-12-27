---
title: Privacy-Preserving Group Recommendations
keywords:
- recommender systems
- group recommendations
- homomorphic encryption
lang: en-US
date-meta: '2022-12-27'
author-meta:
- Jill-Jênn Vie
- Tomas Rigaux
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Privacy-Preserving Group Recommendations" />
  <meta name="citation_title" content="Privacy-Preserving Group Recommendations" />
  <meta property="og:title" content="Privacy-Preserving Group Recommendations" />
  <meta property="twitter:title" content="Privacy-Preserving Group Recommendations" />
  <meta name="dc.date" content="2022-12-27" />
  <meta name="citation_publication_date" content="2022-12-27" />
  <meta property="article:published_time" content="2022-12-27" />
  <meta name="dc.modified" content="2022-12-27T12:47:47+00:00" />
  <meta property="article:modified_time" content="2022-12-27T12:47:47+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Jill-Jênn Vie" />
  <meta name="citation_author_institution" content="SODA, Inria" />
  <meta name="citation_author_orcid" content="0000-0002-9304-2220" />
  <meta name="twitter:creator" content="@jjvie" />
  <meta name="citation_author" content="Tomas Rigaux" />
  <meta name="citation_author_institution" content="SODA, Inria" />
  <link rel="canonical" href="https://jilljenn.github.io/privgrouprec/" />
  <meta property="og:url" content="https://jilljenn.github.io/privgrouprec/" />
  <meta property="twitter:url" content="https://jilljenn.github.io/privgrouprec/" />
  <meta name="citation_fulltext_html_url" content="https://jilljenn.github.io/privgrouprec/" />
  <meta name="citation_pdf_url" content="https://jilljenn.github.io/privgrouprec/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://jilljenn.github.io/privgrouprec/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://jilljenn.github.io/privgrouprec/v/3674fc12b8f69638a7fd5ecebb55f7991075b213/" />
  <meta name="manubot_html_url_versioned" content="https://jilljenn.github.io/privgrouprec/v/3674fc12b8f69638a7fd5ecebb55f7991075b213/" />
  <meta name="manubot_pdf_url_versioned" content="https://jilljenn.github.io/privgrouprec/v/3674fc12b8f69638a7fd5ecebb55f7991075b213/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.bib
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://jilljenn.github.io/privgrouprec/v/3674fc12b8f69638a7fd5ecebb55f7991075b213/))
was automatically generated
from [jilljenn/privgrouprec@3674fc1](https://github.com/jilljenn/privgrouprec/tree/3674fc12b8f69638a7fd5ecebb55f7991075b213)
on December 27, 2022.
</em></small>



## Authors



+ **Jill-Jênn Vie**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-9304-2220](https://orcid.org/0000-0002-9304-2220)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [jilljenn](https://github.com/jilljenn)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [jjvie](https://twitter.com/jjvie)
    <br>
  <small>
     SODA, Inria
  </small>

+ **Tomas Rigaux**
  <br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [Akulen](https://github.com/Akulen)
    <br>
  <small>
     SODA, Inria
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/jilljenn/privgrouprec/issues)
or email to
Jill-Jênn Vie \<jill-jenn.vie@inria.fr\>.


:::


## Abstract {.page_break_before}

In this paper we present privacy-preserving group recommendations so that users can collectively compute recommendations.

## Introduction

In this paper, we present a simple method for computing group recommendations.

## Related Work

Helios [@Adida2008] and Belenios [@doi:10.1007/978-3-030-19052-1_14]

## ElGamal

$$ \frac{\prod_k m_k (pk)^r}{\prod_k (g^r)^{sk}} = \frac{\prod_k m_k g^{r_k r}}{\prod_k g^{r_k r}} = \prod_k m_k = g^{\sum_k m'_k} $$

## Acknowledgements

Thanks Manubot [@{https://greenelab.github.io/meta-review/}].


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

