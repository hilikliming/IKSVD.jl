# IKSVD.jl
This is a Julia Implementation of the Incremental K-SVD Dictionary Learning
Conditioned USPS dataset can be found here: https://www.dropbox.com/sh/4pn9kty1kw8dl67/AADa7YshuXCtW5ouYxcc-Rnpa?dl=0

Or just take the normal USPS data which is 16x16 grayscale... invert the colors, resample to 20x20 and put 4 columns of zero padding on either side and 4 rows above and below the image resulting in images that are 28x28 with 4 pixels of zero padding on all sides just like the MNIST digits.
