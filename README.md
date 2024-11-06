To get this to work:
- Download all files into one folder, so Nail_model_test.blend, Nail_Modeling_Database.db and Nail_Designs are all in the same place
- Open Blender 4.0 and navigate to Scripting, run the script and it should generate a nail model
- To change the design, go to lines 239 to 242 and change the arguments of the functions

Things to note:
- Might not work for newer versions of Blender as they do shaders different now
- To add a texture, color or shape call the addNailXXX function and pass a valid value or open the database through something like DB Browser (SQLite) and add the values there
- To add a design, you also need to add a .png in Nail_Designs
- The source of the nail shapes and answers to most other questions can be found in the .pdf document
