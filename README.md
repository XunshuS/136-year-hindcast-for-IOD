
  This data contains the predicted indices of the Indian Ocean (WIO, EIO and DMI indeces) from the 136-year (1881-2016) retrospective hindcast experiment, by using a tropical intermediate model (Song et al., 2018).
  

Source:
           fc_index.nc
Format:
           netcdf4_classic
Global Attributes:
           title            = 'predicted indices of the Indian Ocean from the 136-year retrospective hindcast experiment'
           Model            = 'Tropical Intermediate Coupled Model (TICM, Song et al.,2018)'
           Initial method   = 'Nudging'
           Assimilated Data = 'HadISST1'
           References       = 'Song X., Chen D., Tang Y., & Liu T., An intermediate coupled model for the tropical ocean-atmosphere system. SCIENCE CHINA: Earth Sciences. doi: 10.1007/s11430-018-9274-6'
Dimensions:
           IniTime  = 1632  (UNLIMITED)
           LeadTime = 13
Variables:
    DMI     
           Size:       1632x13
           Dimensions: IniTime,LeadTime
           Datatype:   double
           Attributes:
                       units     = 'degC'
                       long name = 'DMI index'
    WIO     
           Size:       1632x13
           Dimensions: IniTime,LeadTime
           Datatype:   double
           Attributes:
                       units     = 'degC'
                       long name = 'SSTA averaged over the western IO'
    EIO     
           Size:       1632x13
           Dimensions: IniTime,LeadTime
           Datatype:   double
           Attributes:
                       units     = 'degC'
                       long name = 'SSTA averaged over the eastern IO'
    LeadTime
           Size:       13x1
           Dimensions: LeadTime
           Datatype:   double
           Attributes:
                       long name = 'Lead time'
                       unit      = 'month'
    IniTime 
           Size:       1632x1
           Dimensions: IniTime
           Datatype:   double
           Attributes:
                       long name = 'Initial time'
                       format    = 'yyyymmdd'
  
Reference
Song X., Chen D., Tang Y., & Liu T., An intermediate coupled model for the tropical ocean-atmosphere system. SCIENCE CHINA: Earth Sciences. doi: 10.1007/s11430-018-9274-6.
  
