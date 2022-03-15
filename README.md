
<!-- README.md is generated from README.Rmd. Please edit that file -->

# GCCR001

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vparmac/GCCR-001/master?urlpath=rstudio)

This repository contains the data and code for our paper:

> Valentina Parma, Kathrin Ohla, Maria G. Veldhuizen, Masha Y. Niv,
> Christine E. Kelly, Alyssa J. Bakke, Keiland W. Cooper, Cédric
> Bouysset, Nicola Pirastu, Michele Dibattista, Rishemjit Kaur, Marco
> Tullio Liuzza, Marta Y. Pepino, Veronika Schöpf, Veronica Pereda-Loth,
> Shannon B Olsson, Richard C Gerkin, Paloma Rohlfs Domínguez, Javier
> Albayay, Michael C. Farruggia, Surabhi Bhutani, Alexander W
> Fjaeldstad, Ritesh Kumar, Anna Menini, Moustafa Bensafi, Mari Sandell,
> Iordanis Konstantinidis, Antonella Di Pizio, Federica Genovese, Lina
> Öztürk, Thierry Thomas-Danguin, Johannes Frasnelli, Sanne Boesveldt,
> Özlem Saatci, Luis R. Saraiva, Cailu Lin, Jérôme Golebiowski,
> Liang-Dar Hwang, Mehmet Hakan Ozdener, Maria Dolors Guàrdia,
> Christophe Laudamiel, Marina Ritchie, Jan Havlícek, Denis Pierron,
> Eugeni Roura, Marta Navarro, Alissa A. Nolden, Juyun Lim, KL
> Whitcroft, Lauren R. Colquitt, Camille Ferdenzi, Evelyn V. Brindha,
> Aytug Altundag, Alberto Macchi, Alexia Nunez-Parra, Zara M. Patel,
> Sébastien Fiorucci, Carl M. Philpott, Barry C. Smith, Johan N
> Lundström, Carla Mucignat, Jane K. Parker, Mirjam van den Brink,
> Michael Schmuker, Florian Ph.S Fischmeister, Thomas Heinbockel, Vonnie
> D.C. Shields, Farhoud Faraji, Enrique Enrique Santamaría, William E.A.
> Fredborg, Gabriella Morini, Jonas K. Olofsson, Maryam Jalessi, Noam
> Karni, Anna D’Errico, Rafieh Alizadeh, Robert Pellegrino, Pablo Meyer,
> Caroline Huart, Ben Chen, Graciela M. Soler, Mohammed K. Alwashahi,
> Olagunju Abdulrahman, Antje Welge-Lüssen, Pamela Dalton, Jessica
> Freiherr, Carol H. Yan, Jasper H. B. de Groot, Vera V. Voznessenskaya,
> Hadar Klein, Jingguo Chen, Masako Okamoto, Elizabeth A. Sell, Preet
> Bano Singh, Julie Walsh-Messinger, Nicholas S. Archer, Sachiko Koyama,
> Vincent Deary, S. Craig Roberts, Hüseyin Yanik, Samet Albayrak, Lenka
> Martinec Novákov, Ilja Croijmans, Patricia Portillo Mazal, Shima T.
> Moein, Eitan Margulis, Coralie Mignot, Sajidxa Mariño, Dejan Georgiev,
> Pavan K. Kaushik, Bettina Malnic, Hong Wang, Shima Seyed-Allaei, Nur
> Yoluk, Sara Razzaghi, Jeb M. Justice, Diego Restrepo, Julien W Hsieh,
> Danielle R. Reed, Thomas Hummel, Steven D Munger, John E Hayes,
> (2020). *More than smell. COVID-19 is associated with severe
> impairment of smell, taste, and chemesthesis*. Chemical Senses
> <https://doi.org/10.1093/chemse/bjaa041>

Our pre-print is online here:

> Valentina Parma, Kathrin Ohla, Maria G. Veldhuizen, Masha Y. Niv,
> Christine E. Kelly, Alyssa J. Bakke, Keiland W. Cooper, Cédric
> Bouysset, Nicola Pirastu, Michele Dibattista, Rishemjit Kaur, Marco
> Tullio Liuzza, Marta Y. Pepino, Veronika Schöpf, Veronica Pereda-Loth,
> Shannon B Olsson, Richard C Gerkin, Paloma Rohlfs Domínguez, Javier
> Albayay, Michael C. Farruggia, Surabhi Bhutani, Alexander W
> Fjaeldstad, Ritesh Kumar, Anna Menini, Moustafa Bensafi, Mari Sandell,
> Iordanis Konstantinidis, Antonella Di Pizio, Federica Genovese, Lina
> Öztürk, Thierry Thomas-Danguin, Johannes Frasnelli, Sanne Boesveldt,
> Özlem Saatci, Luis R. Saraiva, Cailu Lin, Jérôme Golebiowski,
> Liang-Dar Hwang, Mehmet Hakan Ozdener, Maria Dolors Guàrdia,
> Christophe Laudamiel, Marina Ritchie, Jan Havlícek, Denis Pierron,
> Eugeni Roura, Marta Navarro, Alissa A. Nolden, Juyun Lim, KL
> Whitcroft, Lauren R. Colquitt, Camille Ferdenzi, Evelyn V. Brindha,
> Aytug Altundag, Alberto Macchi, Alexia Nunez-Parra, Zara M. Patel,
> Sébastien Fiorucci, Carl M. Philpott, Barry C. Smith, Johan N
> Lundström, Carla Mucignat, Jane K. Parker, Mirjam van den Brink,
> Michael Schmuker, Florian Ph.S Fischmeister, Thomas Heinbockel, Vonnie
> D.C. Shields, Farhoud Faraji, Enrique Enrique Santamaría, William E.A.
> Fredborg, Gabriella Morini, Jonas K. Olofsson, Maryam Jalessi, Noam
> Karni, Anna D’Errico, Rafieh Alizadeh, Robert Pellegrino, Pablo Meyer,
> Caroline Huart, Ben Chen, Graciela M. Soler, Mohammed K. Alwashahi,
> Olagunju Abdulrahman, Antje Welge-Lüssen, Pamela Dalton, Jessica
> Freiherr, Carol H. Yan, Jasper H. B. de Groot, Vera V. Voznessenskaya,
> Hadar Klein, Jingguo Chen, Masako Okamoto, Elizabeth A. Sell, Preet
> Bano Singh, Julie Walsh-Messinger, Nicholas S. Archer, Sachiko Koyama,
> Vincent Deary, S. Craig Roberts, Hüseyin Yanik, Samet Albayrak, Lenka
> Martinec Novákov, Ilja Croijmans, Patricia Portillo Mazal, Shima T.
> Moein, Eitan Margulis, Coralie Mignot, Sajidxa Mariño, Dejan Georgiev,
> Pavan K. Kaushik, Bettina Malnic, Hong Wang, Shima Seyed-Allaei, Nur
> Yoluk, Sara Razzaghi, Jeb M. Justice, Diego Restrepo, Julien W Hsieh,
> Danielle R. Reed, Thomas Hummel, Steven D Munger, John E Hayes,
> (2020). *More than smell. COVID-19 is associated with severe
> impairment of smell, taste, and chemesthesis*. MedRxiv, Accessed 09
> Jul 2020. Online at <https://doi.org/10.1101/2020.05.04.20090902>

Other materials, such as the preregistration and translations of the
questionnaire may be found here:

> Parma, V., Ohla, K., Veldhuizen, M., Reed, D., Liuzza, M. T., &
> Houser, D. (2020, July 8). *GCCR001-* *More than smell. COVID-19 is
> associated with severe impairment of smell, taste, and chemesthesis*.
> osf.io, Accessed 09 Jul 2020 Online at
> <https://doi.org/10.17605/OSF.IO/A3VKW>

### How to cite

Please cite this compendium as:

> Valentina Parma, Kathrin Ohla, Maria G. Veldhuizen, Masha Y. Niv,
> Christine E. Kelly, Alyssa J. Bakke, Keiland W. Cooper, Cédric
> Bouysset, Nicola Pirastu, Michele Dibattista, Rishemjit Kaur, Marco
> Tullio Liuzza, Marta Y. Pepino, Veronika Schöpf, Veronica Pereda-Loth,
> Shannon B Olsson, Richard C Gerkin, Paloma Rohlfs Domínguez, Javier
> Albayay, Michael C. Farruggia, Surabhi Bhutani, Alexander W
> Fjaeldstad, Ritesh Kumar, Anna Menini, Moustafa Bensafi, Mari Sandell,
> Iordanis Konstantinidis, Antonella Di Pizio, Federica Genovese, Lina
> Öztürk, Thierry Thomas-Danguin, Johannes Frasnelli, Sanne Boesveldt,
> Özlem Saatci, Luis R. Saraiva, Cailu Lin, Jérôme Golebiowski,
> Liang-Dar Hwang, Mehmet Hakan Ozdener, Maria Dolors Guàrdia,
> Christophe Laudamiel, Marina Ritchie, Jan Havlícek, Denis Pierron,
> Eugeni Roura, Marta Navarro, Alissa A. Nolden, Juyun Lim, KL
> Whitcroft, Lauren R. Colquitt, Camille Ferdenzi, Evelyn V. Brindha,
> Aytug Altundag, Alberto Macchi, Alexia Nunez-Parra, Zara M. Patel,
> Sébastien Fiorucci, Carl M. Philpott, Barry C. Smith, Johan N
> Lundström, Carla Mucignat, Jane K. Parker, Mirjam van den Brink,
> Michael Schmuker, Florian Ph.S Fischmeister, Thomas Heinbockel, Vonnie
> D.C. Shields, Farhoud Faraji, Enrique Enrique Santamaría, William E.A.
> Fredborg, Gabriella Morini, Jonas K. Olofsson, Maryam Jalessi, Noam
> Karni, Anna D’Errico, Rafieh Alizadeh, Robert Pellegrino, Pablo Meyer,
> Caroline Huart, Ben Chen, Graciela M. Soler, Mohammed K. Alwashahi,
> Olagunju Abdulrahman, Antje Welge-Lüssen, Pamela Dalton, Jessica
> Freiherr, Carol H. Yan, Jasper H. B. de Groot, Vera V. Voznessenskaya,
> Hadar Klein, Jingguo Chen, Masako Okamoto, Elizabeth A. Sell, Preet
> Bano Singh, Julie Walsh-Messinger, Nicholas S. Archer, Sachiko Koyama,
> Vincent Deary, S. Craig Roberts, Hüseyin Yanik, Samet Albayrak, Lenka
> Martinec Novákov, Ilja Croijmans, Patricia Portillo Mazal, Shima T.
> Moein, Eitan Margulis, Coralie Mignot, Sajidxa Mariño, Dejan Georgiev,
> Pavan K. Kaushik, Bettina Malnic, Hong Wang, Shima Seyed-Allaei, Nur
> Yoluk, Sara Razzaghi, Jeb M. Justice, Diego Restrepo, Julien W Hsieh,
> Danielle R. Reed, Thomas Hummel, Steven D Munger, John E Hayes,
> (2020). *Compendium of R code and data for More than smell. COVID-19
> is associated with severe impairment of smell, taste, and
> chemesthesis*. Accessed 09 Jul 2020. Online at
> <https://doi.org/xxx/xxx>

## Contents

The **analysis** directory contains:

  - [:file\_folder: paper](/analysis/paper): R Markdown source document
    for manuscript. Includes code to reproduce the figures and tables
    generated by the analysis. It also has a rendered version,
    `paper.docx`, suitable for reading (the code is replaced by figures
    and tables in this file)
  - [:file\_folder: data](/analysis/data): Data used in the analysis.
  - [:file\_folder: figures](/analysis/figures): Plots and other
    illustrations
  - [:file\_folder:
    supplementary-materials](/analysis/supplementary-materials):
    Supplementary materials including notes and other documents prepared
    and collected during the analysis.

## How to run in your broswer or download and run locally

This research compendium has been developed using the statistical
programming language R. To work with the compendium, you will need
installed on your computer the [R
software](https://cloud.r-project.org/) itself and optionally [RStudio
Desktop](https://rstudio.com/products/rstudio/download/).

The simplest way to explore the text, code and data is to click on
[binder](https://mybinder.org/v2/gh/vparmac/GCCR-001/master?urlpath=rstudio)
to open an instance of RStudio in your browser, which will have the
compendium files ready to work with. Binder uses rocker-project.org
Docker images to ensure a consistent and reproducible computational
environment. These Docker images can also be used locally.

You can download the compendium as a zip from from this URL:
[master.zip](/archive/master.zip). After unzipping: - open the `.Rproj`
file in RStudio - run `devtools::install()` to ensure you have the
packages this analysis depends on (also listed in the
[DESCRIPTION](/DESCRIPTION) file). - finally, open
`analysis/paper/paper.Rmd` and knit to produce the `paper.docx`, or run
`rmarkdown::render("analysis/paper/paper.Rmd")` in the R console

### Licenses

**Text and figures :**
[CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)

**Code :** See the [DESCRIPTION](DESCRIPTION) file

**Data :** [CC-0](http://creativecommons.org/publicdomain/zero/1.0/)
attribution requested in reuse

### Contributions

We welcome contributions from everyone. Before you get started, please
see our [contributor guidelines](CONTRIBUTING.md). Please note that this
project is released with a [Contributor Code of Conduct](CONDUCT.md). By
participating in this project you agree to abide by its terms.
