# Workflow

The create Parallax 3DPrint Material workflow consists of the following steps:

1. Create a "Capture3DTool" asset
2. Drag into the scene
3. Adjust the Size property
4. Create four 3DPrintRenderTargets
5. Choose show only Actors
6. bAuto Create Material
7. Choose algorithm type
8. Create


## 1) Create a Capture3DTool asset
Right-click in the content browser and select the blueprint class, filter and create a "**Capture3DTool**" asset. 
![img](https://raw.githubusercontent.com/handsomeXZ/Parallax3DPrint_Demo/main/Documentation/imgs/1.png)
![img](https://raw.githubusercontent.com/handsomeXZ/Parallax3DPrint_Demo/main/Documentation/imgs/2.png)


## 2) Drag into the scene
Drag the **Capture3DTool** into the scene and aim at the scene where the corresponding material needs to be created. 
![img](https://raw.githubusercontent.com/handsomeXZ/Parallax3DPrint_Demo/main/Documentation/imgs/3.png)

## 3) Adjust the Size property
Adjust the Size property of **Capture3DTool** so that the shape box contains the items to be captured. 
![img](https://raw.githubusercontent.com/handsomeXZ/Parallax3DPrint_Demo/main/Documentation/imgs/4.png)

## 4) Create four 3DPrintRenderTargets
Create the required four **3DPrintRenderTargets** for **Capture3DTool**. 
![img](https://raw.githubusercontent.com/handsomeXZ/Parallax3DPrint_Demo/main/Documentation/imgs/5.png)

## 5) Choose show only Actors
Choose show only Actors which will be captured. 
![img](https://raw.githubusercontent.com/handsomeXZ/Parallax3DPrint_Demo/main/Documentation/imgs/6.png)
## 6) bAuto Create Material
Choose whether to automatically generate the corresponding material. 


## 7) Choose algorithm type
If you choose to automatically generate materials in **5)**, you need to choose a 3DPrint algorithm (**default**/**Halton**). 

![img](https://raw.githubusercontent.com/handsomeXZ/Parallax3DPrint_Demo/main/Documentation/imgs/7.png)
## 8) Create
Click "**Create**" to generate the corresponding asset. 
![img](https://raw.githubusercontent.com/handsomeXZ/Parallax3DPrint_Demo/main/Documentation/imgs/8.png)
![img](https://raw.githubusercontent.com/handsomeXZ/Parallax3DPrint_Demo/main/Documentation/imgs/9.png)
![img](https://raw.githubusercontent.com/handsomeXZ/Parallax3DPrint_Demo/main/Documentation/imgs/10.png)

## Important/Additional Notes:
Sometimes there is a problem with the generated depth map, this is due to the frame drop caused by the freeze, please try to **Create** again