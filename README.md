# Point Cloud on Human Action Dataset

1. Install Human to mesh model 
    ```
    conda create -n human_mesh python=2.7
    conda activate human_mesh
    pip install -r requirements.txt
    cd opendr_77/ 
    python setup.py build
    python setup.py install
    pip install tensorflow==1.3.0
    cd ../
    python -m demo --img_path data/coco1.png
    ```

2. Install blender to eazy visualization of 3D object
    
    <img src="doc/original_output.png" alt="drawing" width="400"/> &nbsp;

    <img src="doc/after_upsampling.png" alt="drawing" width="400"/> 
    Zoomed into -->
    <img src="doc/zoomed.png" alt="drawing" width="400"/> 
2. (Optional) Up-sampling the vertices surfaces 