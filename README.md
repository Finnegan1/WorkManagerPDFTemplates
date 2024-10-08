# WorkManagerPDFTemplates

This Repository contains Templates for the generation of PDF in the WorkManager application.

## Templates

Every Template is in its own folder. The folder name is the name of the template. This name has to be unique.

### Template Folder Structure

Every template folder has to contain a `template.hbs` file. This file contains the template for the PDF.

Every template folder can contain any number of images. These images can be used in the template.hbs file.

### Template File

The template file is a handlebars file.
This file is used to generate the PDF.

the following variables are available:

- currentDate: The current date (type: string)
- startDate: The start date of the work (type: string)
- endDate: The end date of the work (type: string)
- image: The image of the area (the base64 encoded image data) (type: string)
- description: The description of the area (type: string)
- workDescription: The work description of the area (type: string)
- forstrevier: The forestry range of the area (type: string)
- information: The information of the area (type: string)
- forestSection: The forest section of the area (type: string)
- trailsInArea: A list of the trails in the area (type: string[])