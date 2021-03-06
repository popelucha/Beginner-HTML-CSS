1. Click on the image icon next to the **+** sign. This is where you can see the pictures that can be used on your website. For now you can use the picture included with the project. 
2. Go to the index.html file in the code panel. After the `</ul>` tag, type the following: 
   ```html
      <img src="tito.png" alt="Tito the dog" width="100px" />
   ```
   ![](/assets/ImgTito2.png)
 Notice that the `<img>` tag is different from the other tags you've used so far: 
   * There is no closing `</img>` tag. Instead it is **self closing**: the opening tag has `/>` at the end. This is because there is no "start" and "end" like there is when you are putting text on the page. 
   * The tag contains three extra pieces of information inside it called **attributes**. The `src` attribute tells the browser what file to use for the picture. The `alt` attribute is a short description that the browser will show if it cannot display the picture. 
4. What do you think the `width` attribute does? \(Hint: **px** is short for **pixels**, the teeny-tiny dots that make up your screen\) Try experimenting with different numbers! Don't delete the letters `px`. 
5. To add a picture of your own to the website, click on the image icon again, and click "Add Image". Click "Upload" and then select "Click To Select Files". Select the file on your computer that you want to upload and click "Open". Click "Done" when you are finished uploading files, and then click Save to save your work.

  **Note:** Check the name of your file before uploading it and **rename** it first if you need to. It's a good idea to have filenames that don't contain any spaces. Plus if you've downloaded a picture from the internet, it may be called something like "177823k-iewnf8832n2-3dkewnfwe512.png" which is not very easy to type!
 ![](/assets/UploadFilesWider.png)
6. Once you have uploaded a picture you can add it to your website using the `<img>` tag as before. Change the value of the `src` attribute so that it exactly matches the name of the file with your picture. Change the value of the `alt` attribute to a short description of the picture. _Important:_ Attribute values like the filename and the alt text must be inside quotation marks!



