# Assignment4


Code:
curl https://southcentralus.api.cognitive.microsoft.com/customvision/v3.0/Prediction/640406b2-5da4-4777-98f1-0b3a0e98c690/classify/iterations/Iteration2/url \
-H "Prediction-Key: 332f27e0a7674545b728417a4812049e" \
-H "Content-Type: application/json" \
-d "{'url' : 'https://raw.githubusercontent.com/MicrosoftDocs/mslearn-classify-images-with-the-custom-vision-service/master/test-images/VanGoghTest_02.jpg'}" \
| jq '.'


Images Used in Project 
![Picasso_01](https://user-images.githubusercontent.com/56988970/88468813-0d8e7b80-ceb7-11ea-84f6-0500b1a562a9.jpg)
![Picasso_02](https://user-images.githubusercontent.com/56988970/88468814-0d8e7b80-ceb7-11ea-9b2f-9015f13c1eef.jpg)
![Picasso_03](https://user-images.githubusercontent.com/56988970/88468815-0e271200-ceb7-11ea-83cd-8d33d762a002.JPG)
![Picasso_04](https://user-images.githubusercontent.com/56988970/88468816-0e271200-ceb7-11ea-886b-77e205da90f8.jpg)
![Picasso_05](https://user-images.githubusercontent.com/56988970/88468817-0e271200-ceb7-11ea-8590-5fa4494335a1.JPG)
![Picasso_06](https://user-images.githubusercontent.com/56988970/88468818-0e271200-ceb7-11ea-85a7-cf5aa54194bb.jpg)
![Picasso_07](https://user-images.githubusercontent.com/56988970/88468819-0f583f00-ceb7-11ea-8acb-ab81aff29589.jpg)
![Pollock_01](https://user-images.githubusercontent.com/56988970/88468822-167f4d00-ceb7-11ea-9c94-fc043cd1ab68.jpg)
![Pollock_02](https://user-images.githubusercontent.com/56988970/88468823-17b07a00-ceb7-11ea-9f09-e56b859d8e97.jpg)
![Pollock_03](https://user-images.githubusercontent.com/56988970/88468824-17b07a00-ceb7-11ea-8486-eac429477d4b.jpg)
![Pollock_04](https://user-images.githubusercontent.com/56988970/88468825-18491080-ceb7-11ea-812b-04a63656caa3.png)
![Pollock_05](https://user-images.githubusercontent.com/56988970/88468827-1aab6a80-ceb7-11ea-876d-c54be7d37e75.jpg)
![Pollock_06](https://user-images.githubusercontent.com/56988970/88468828-1b440100-ceb7-11ea-8c85-890d8d8cc88e.jpg)
![Rembrandt_01](https://user-images.githubusercontent.com/56988970/88468829-1da65b00-ceb7-11ea-9f2e-d80db8780a06.jpg)

Test Images
![FlowersTest](https://user-images.githubusercontent.com/56988970/88468836-2a2ab380-ceb7-11ea-8e70-f7c502d479b0.jpg)
![PicassoTest_01](https://user-images.githubusercontent.com/56988970/88468837-2ac34a00-ceb7-11ea-96c4-9195a8e31a6f.jpg)
![PicassoTest_02](https://user-images.githubusercontent.com/56988970/88468838-2ac34a00-ceb7-11ea-9324-7ee2b24cca2f.jpg)
![PollockTest_01](https://user-images.githubusercontent.com/56988970/88468839-2b5be080-ceb7-11ea-90a2-cef3bc35624c.jpg)
![RembrandtTest_01](https://user-images.githubusercontent.com/56988970/88468840-2b5be080-ceb7-11ea-9a96-9a2496d5378d.jpg)
![VanGoghTest_01](https://user-images.githubusercontent.com/56988970/88468841-2bf47700-ceb7-11ea-932c-0b6259f194fd.jpg)
![VanGoghTest_02](https://user-images.githubusercontent.com/56988970/88468842-2bf47700-ceb7-11ea-9e90-0b724b3430c6.jpg)
