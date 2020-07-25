# Assignment4

Image1:
https://raw.githubusercontent.com/MicrosoftDocs/mslearn-classify-images-with-the-custom-vision-service/master/test-images/PicassoTest_02.jpg

Image2:
https://raw.githubusercontent.com/MicrosoftDocs/mslearn-classify-images-with-the-custom-vision-service/master/test-images/RembrandtTest_01.jpg

Image3:
https://raw.githubusercontent.com/MicrosoftDocs/mslearn-classify-images-with-the-custom-vision-service/master/test-images/PollockTest_01.jpg

Code:
curl https://southcentralus.api.cognitive.microsoft.com/customvision/v3.0/Prediction/640406b2-5da4-4777-98f1-0b3a0e98c690/classify/iterations/Iteration2/url \
-H "Prediction-Key: 332f27e0a7674545b728417a4812049e" \
-H "Content-Type: application/json" \
-d "{'url' : 'https://raw.githubusercontent.com/MicrosoftDocs/mslearn-classify-images-with-the-custom-vision-service/master/test-images/VanGoghTest_02.jpg'}" \
| jq '.'
