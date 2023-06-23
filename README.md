# Underwater-Image-Enhancement
Towards Domain Adversarial learning for Underwater Image Enhancement

> Set the Environment using
> 
>  conda env create --name envname --file=environment.yaml

> Data preparation
> 
> 1. Go to data/data Preparation
> 2. To create the dataset of 6 water-type of underwater images
> >  **Run:** python data_water_type.ipynb
> 3. To create csv file run:
>  > **Run:** python data_to_csv.ipynb
> 4. put the raw and ref folders in data folder


> Train the modle
>> python main.py
>
> test the model
>> python test.py
