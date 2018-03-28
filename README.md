# matlab-wavefront-obj-loader
MATLAB code for loading .obj .

Doesn't handle mtl
## Example 
 mesh = readObj('2haorenti.obj');  % read .obj
 
figure;

patch('Faces',mesh.f.v,'Vertices',mesh.v,'FaceAlpha',0); % plotting the 

hold on;

axis equal
![image](https://github.com/botaow24/matlab-wavefront-obj-loader/blob/master/example.png)
## Speed
9.116 seconds for a 42,281 vertices mesh
