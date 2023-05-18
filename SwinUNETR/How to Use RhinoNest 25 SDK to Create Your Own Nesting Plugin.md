## How to Use RhinoNest 2.5 SDK to Create Your Own Nesting Plugin

  
# How to Use RhinoNest 2.5 SDK to Create Your Own Nesting Plugin
 
RhinoNest 2.5 is a powerful and flexible nesting software for Rhinoceros that allows you to optimize the use of material and reduce waste. But did you know that you can also create your own nesting plugin using RhinoNest 2.5 SDK?
 
## rhinonest 2.5 crack


[**DOWNLOAD**](https://www.google.com/url?q=https%3A%2F%2Fcinurl.com%2F2tKGdV&sa=D&sntz=1&usg=AOvVaw0pcJ7UBHAbyBmC8u-IDVzE)

 
RhinoNest 2.5 SDK (Software Development Kit) is a tool that enables any RhinoNest user to develop their own nesting application. You can access all the nesting features of RhinoNest 2.5 and customize them according to your needs. You can also use it inside a GH .Net component or in GH Python to integrate it with Grasshopper, the parametric modeling plugin for Rhinoceros.
 
In this article, we will show you an example of how to create your own nesting command using C# and Rhinoceros 5.0. You will need to have RhinoNest 2.5 and RhinoNest for GH installed on your computer. You can download them from [www.rhinonest.com](https://www.rhinonest.com). You will also need a C# compiler, such as Visual Studio.
 
## Step 1: Create a new project in Visual Studio
 
Open Visual Studio and create a new project of type Class Library (.NET Framework). Name it MyNestingPlugin and click OK.
 
## Step 2: Add references to RhinoCommon and RhinoNestTools
 
In the Solution Explorer, right-click on References and select Add Reference. Browse to the folder where Rhinoceros 5.0 is installed (usually C:\Program Files\Rhinoceros 5\System) and select RhinoCommon.dll. Click OK.
 
Then, right-click on References again and select Add Reference. Browse to the folder where RhinoNest 2.5 is installed (usually C:\Program Files\TDM Solutions\RhinoNest) and select RhinoNestTools.dll. Click OK.
 
## Step 3: Write the code for the nesting command
 
In the Solution Explorer, right-click on Class1.cs and rename it to MyNestingCommand.cs. Double-click on it to open it in the code editor.
 
Replace the existing code with the following:
  ```csharp using System; using System.Collections.Generic; using System.Linq; using System.Text; using System.Threading.Tasks; using Rhino; using Rhino.Commands; using Rhino.Geometry; using Rhino.Input; using Rhino.Input.Custom; using TDM.RhinoNest;  namespace MyNestingPlugin {     public class MyNestingCommand : Command     {         public MyNestingCommand()                      // TODO: Complete command constructor                   public override string EnglishName                      get  return "MyNestingCommand";                    protected override Result RunCommand(RhinoDoc doc, RunMode mode)         {             // TODO: Start here modifying the behaviour of your command.             // ---             // Get the curves to nest             GetObject go = new GetObject();             go.SetCommandPrompt("Select curves to nest");             go.GeometryFilter = ObjectType.Curve;             go.GetMultiple(1, 0);             if (go.CommandResult() != Result.Success)                 return go.CommandResult();              // Create a list of curves             List<curve> curves = new List<curve>();
            for (int i = 0; i < go.ObjectCount; i++)
            
                Curve curve = go.Object(i).Curve();
                if (curve != null)
                    curves.Add(curve);

            // Get the sheet size
            GetPoint gp = new GetPoint();
            gp.SetCommandPrompt("Pick lower left corner of sheet");
            gp.Get();
            if (gp.CommandResult() != Result.Success)
                return gp.CommandResult();
            Point3d pt1 = gp.Point();

            gp.SetCommandPrompt("Pick upper right corner of sheet");
            gp.SetBasePoint(pt1, true);
            gp.DrawLineFromPoint(pt1, true);
            gp.Get();
            if (gp.CommandResult() != Result.Success)
                return gp.CommandResult();
            Point3d pt2 = gp.Point();

            // 0f148eb4a0


</curve></curve>
