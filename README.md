# quarto-templates

Collection of preset templates for quarto documents

## Developing templates:

1.  Create new folder with descriptive name for template.
2.  In that folder, create a template.qmd file that has the essential elements you want for the template.
3.  Add any additional files or folders that are needed for the template: css, scss, etc.
4.  Push changes to github repo for use in Quarto projects.

## To use a template:

1.  In your Quarto project \> Terminal.
2.  Run the following command to add the template to your project:
    1.   **`quarto template add jyuill/quarto-templates/<folder of template>`**
    2.  (RStudio will automatically look in github for the folder for downloading)
3.  Terminal: Provide folder name when prompted.
4.  The files in the github template folder will be added to your project in the new folder, with the template.qmd renamed to match the folder name.
5.  Use the template file as starting point in your Quarto project.

**That's it!** You can get more complicated by incorporating styling, developing more complete extensions, but that is the basic idea. Works great for simple templates that help with consistency and quick start.

## Next Steps

-   table examples: gt, others
-   tabbed setup
