# dev-portal-Export-Third-Parties-sample



## Requirements

Opening .ipynb files requires:
1. Google account
2. [Google Colaboratory][1]

[1]: https://workspace.google.com/marketplace/app/colaboratory/1014160490159?pann=ogb


## Installation

1.  Copy the repository link, open Command Prompt, go to the location where file will be copied and execute git clone command:

```shell
git clone https://github.com/kyriba/dev-portal-Export-Third-Parties-sample.git
```

2. Import Third_parties_exporting.ipynb file into your Google Drive.

3. Open config.csv file and input your client credentials by replacing the highlighted items with your client_id and client_secret, separated by the coma. Config file should look like this:

![config.png](config.png)

4. Open the jupyter notebook with Google Collab.

5. In the Table of Content on the left, click on the folder logo ![files.png](files.png) which opens Files section, find 'content' folder and upload config.csv file into this folder.

6. Run application. You can run the whole application: Runtime -> Run all, or execute separated cells.

> ⚠️  _Please notice that Python is script language and code will be executed row by row or in the order you will run the cells._

7. Find the generated token under "Connect" cell and the sample results in the next ones. The "Launch and Compare Third Parties and Process Template reports" will display the comparison results between both samples, and the next two "Show retrieved..." cells visualize the launched reports with customizable amount of rows displayed in CSV tables.

> ⚠️  _By default account information retrieved by Process Template API is not displayed in the results for user convenience._


