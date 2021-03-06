# Outlier Removal Using InterQuartile Range        
        

 **Project 2 : UCS633**
        
        
        Submitted By: **Kshitiz Varshney 101703295**
        
        ***
        pypi: <https://pypi.org/project/outlierRemoval-kvarshney-101703295/>
        ***
        
        ## InterQuartile Range (IQR) Description
        
        Any set of data can be described by its five-number summary. These five numbers, which give you the information you need to find patterns and outliers, consist of:
        
        The minimum value of the dataset.
        <br>
        The first quartile Q1, which represents a quarter(25%) of the way through the list of all data.
        <br>
        The median of the data set, which represents the midpoint(50%) of the whole list of data.
        <br>
        The third quartile Q3, which represents three-quarters(75%) of the way through the list of all data.
        <br>
        The maximum value of the data set.
        <br>
        <br>
        These five values helps in determining exceptional(outliers) elements present in our dataset.
        
        ## Calculation of IQR
        
        IQR = Q3 – Q1
        <br>
        MIN = Q1 - (1.5*IQR)
        <br>
        MAX = Q3 + (1.5*IQR)
        <br>
        
        ## Installation
        
        Use the package manager [pip](https://pip.pypa.io/en/stable/) to install outlierRemoval-kvarshney-101703295.
        
        ```bash
        pip install outlierRemoval-kvarshney-101703295
        ```
        <br>
        
        ## How to use this package:
        
        outlierRemoval-kvarshney-101703295 can be run as shown below:
        
        
        ### In Command Prompt
        ```
        >> outlierRemoval dataset.csv
        ```
        <br>
        
        
        ## Sample dataset
        
        Marks | Students 
        :------------: | :-------------:
        3  | Student 1
        57 | Student 2
        65 | Student 3
        98 | Student 4
        43 | Student 5
        44 | Student 6
        54 | Student 7
        1  | Student 8
        
        <br>
        
        
        ## Output Dataset after Removal
        
        Marks | Students 
        :------------: | :-------------:
        57 | Student2
        65 | Student3
        98 | Student4
        43 | Student5
        44 | Student6
        54 | Student7
        
        <br>
        
        It is clearly visible that the rows containing Student1 and Student8 have been removed due to them being Outliers.
        
        
        ## License
        [MIT](https://choosealicense.com/licenses/mit/)