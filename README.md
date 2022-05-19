# Webaverse Pets
![1.png](https://webaverse.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F0ff6758b-23a7-47e2-9f10-e117ca79d90f%2Fimage_2022-02-19_000225.png?table=block&id=e74f208b-602b-4735-b1e5-c991e07e61c1&spaceId=5ebd5855-84d8-460f-8af7-2e686fd0ecc5&width=2000&userId=&cache=v2)
## Hosted Webaverse Environments:

To get started with a personalized pet, follow these simple steps.

1. Go to the GitHub “fox” example repo: [https://github.com/webaverse/fox](https://github.com/webaverse/fox) and fork it to your personal account.

![2.png](https://webaverse.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F260ade28-b032-4fa7-9255-7303626e7c31%2F1.png?table=block&id=185c2a54-a322-4621-93ee-a3af36eddeb6&spaceId=5ebd5855-84d8-460f-8af7-2e686fd0ecc5&width=2000&userId=&cache=v2)

2.. Add your own .glb model into the repo —- Or just use one of the existing models that’s already there. 
3. Next, open the .metaversefile and edit it.

![3.png](https://webaverse.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F23897c24-81fd-4df2-b255-d12a02664245%2F2.png?table=block&id=0788970d-1924-4632-a01d-fc24319d164b&spaceId=5ebd5855-84d8-460f-8af7-2e686fd0ecc5&width=2000&userId=&cache=v2)

4. Search the file for “.glb” ****and update the reference ******from “****.glb***” to the name of the model you want to use (i.e., ***“mymodel.glb”* ).  ****Then save and commit the changes. For more information about .metaversefile, look [here](https://www.notion.so/metaversefile-628e2c46f49345dfa68a2eab7b89d3f5).
![image](https://user-images.githubusercontent.com/64185677/169270615-1a38d671-cc5f-4e05-b522-f57858f9ddda.png)

5. Your model is now ready to be used in any Webaverse scene! There’s just one last step required in order to reference it from a hosted Webaverse installation: enable the GitHub Page on your repo. Head over to the settings for the repo, go to the Pages section, set the branch as master and save it. Finally, make a note of the GitHub page URL for later.

![image](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/981b5832-a6a4-4a89-8314-edd6a10a6e30/bandicam_2022-02-19_22-29-09-026.mp4)

6. You can use any of our template scenes or make your own. To add a model in a template scene, go the **“app/scenes”** folder in your cloned Webaverse app and open any of the .scn files.
7. Copy and paste this into the .scn file right before the closing “]” bracket.

```jsx
,{
	"position": [
		0,
		1,
		0
	],
	"quaternion": [
		0,
		0,
		0,
		1
	],
	"start_url": "https://webaverse.github.io/fox/"
}
```

1. Set “start_url” to the url of the GitHub Page for your repository. You can also adjust the starting position and rotation of the model based on where you want it in your scene. Now save the file and you’re good to go. 
2. Go to [https://app.webaverse.com](https://app.webaverse.com) or some other hosted version of the app, drag your .scn file into the browser and experience your model brought to life.

## Local Webaverse Environments:

1. Go to the GitHub repo: [https://github.com/webaverse/fox](https://github.com/webaverse/fox) and download the repo as **a zip.**
2. Extract the zip folder into your already available Webaverse **“app”** folder.
3. Add your own .glb model into the extracted folder —- Or just use one of the existing models that’s already there. 
4. Your model is now ready to be used in any Webaverse scene! You can use any of our template scenes or make your own. To add a model in a template scene, go the **“app/scenes”** folder in your cloned Webaverse app and open any of the .scn files.
5. Now copy and paste this into the .scn file right before the closing “]” bracket.

```jsx
,{
	"position": [
		0,
		1,
		0
	],
	"quaternion": [
		0,
		0,
		0,
		1
	],
	"start_url": "/fox-master/"
}
```

1. You can also adjust the starting position and rotation of the model based on where you want it in your scene. Now save the file and you’re good to go. Run the app, enter the edited scene and enjoy!

**Checkout our walkthrough video on how to create a pet:**

[walkthrough video on how to create a pet](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8fa308f5-30c8-407c-acc2-1898681dbacb/ezgif.com-gif-maker_(1).mp4O)

### **Relevant Apps:**

You can also visit these relevant apps that we have for pets:

- https://github.com/webaverse/fox
- https://github.com/webaverse/lisk
