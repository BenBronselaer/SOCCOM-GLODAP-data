This folder contain the post-processed observational data for the manuscript 
'Impact of wind and meltwater on recent observed physical and chemical evolution of the Southern Ocean'

The files included are:

- SOCCOM_data.nc : SOCCOM float data, beginning in January 2014, from the LoRes March 12 2019 snapshot gridded onto a 8x3 horizontal 
                  grid and 23 vertical levels
                  (original data: https://doi:10.6075/J01G0JKT)
                    
                    
                    
                    
- GLODAP_data.nc : pre-2005 GLODAPv2 quality-controlled shipboard data gridded onto a 8x3 horizontal 
                  grid and 23 vertical levels
                  (original data from: https://odv.awi.de/data/ocean/glodap-v2-bottle-data/)




- error_data.nc : 1 x sigma error estimates for the difference between the SOCCOM and GLODAPc2 shipboard data. 
                The systematic and random errors are as quoted in the manuscript (although random errors mostly negligible 
                due to the number of data points in each grid box. The errors due to natural variability, as diagnosed from a 
                30-member ESM2M large ensemble simulation, are give as *_variability. The errors due to different interpolation methods
                are given as *_interpolation. The total errors, including all contributions added in quadrature, are given as
                *_total_error
                
                
                
               
               
Any issues/comments/corrections/questions, email me at bbronselaer@email.arizona.edu

