# NIR-spectroscopy-Crop-Identification
The goal of this assignment is to use non-destructive near infrared (NIR) spectroscopy measurements to predict cherry dry matter ratio at post-harvest for seven cherry varieties.
The data for this assignment was provided by Dr. Irwin Donales-Gonzalez, another UCD BAE professor. Several years ago his team used the Felix F-750 Produce Quality Meter to characterize eight commercially produced cherry varieties: Brooks, Tulare, Corals, Rainer, Somba, Bing, Garnet, and Sweet. Data from seven of these varieties are included in this assignment. The Felix F-750 Produce Quality Meter uses NIR spectroscopy to collect the reflectance and absorbance of fruit in response to illumination with NIR light. Aborbance and reflectance measurements are recorded across a number of different wavelengths ranging from 310 to 1200 nm. Here, we will use a subset of this absorbance data ranging from 351 nm to 1137 nm at ~3 nm bands. In addition to NIR spectroscopy data, Dr. Donales-Gonzalez' team collected information on physico-chemical properties of cherries related to quality. In this assignment, we will focus on "dry matter ratio" which is the fractional total of all solids in a fruit minus its water. Dry matter ratio has been shown in the past to relate to perceived fruit sensory quality as it integrates soluble sugar content, with other carbohydrate and acid profiles (see Escribano et al., 2017).

Check out this informative blog post (https://felixinstruments.com/blog/nir-for-cherries/#:~:text=For%20this%20reason%2C%20sugar%20remains,quality%20in%20storage%20and%20retailing.&text=In%20sweet%20cherries%2C%2080%25%20of,%2C%20acids%2C%20and%20some%20proteins.) for more information on how NIR spectroscopy can be used for non-destructive fruit quality assessment. While it is written by a manufacturer of NIR spectrscopy instruments it lists a number of peer reviewed papers on the topic, including one on which Dr. David Slaughter in the UCD BAE department is a co-author.

From a modeling perspective, spectroscopic measurements often generate many potential predictive variables that are spectrally correlated (we'll cover this more in upcoming lectures). In our dataset there are 263 spectral bands, each of which could potentially be used to predict dry matter content. However, bands that neighbor each other spectrally are often highly correlated and, consequently, share similar relationships with the variable that you are trying to predict.
