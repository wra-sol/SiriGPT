<p align="center"><a href="#"><img src="https://user-images.githubusercontent.com/48920263/228290334-e8673b16-afd2-4039-8a17-52fbf5d832e5.png" draggable="false" ondragstart="return false;" alt="SiriGPT Title" title="SiriGPT" /></a></p>

The technologies driving the new wave of chatbots have been percolating for years. But the release of [ChatGPT][chaGPT] really opened people’s eyes. It set off a new arms race across Silicon Valley. However, AI is not new as voice assistants like [Siri][apple-siri] have been here for quite a long time. In the same vein though, most will agree that Siri does not pack a lot of intelligence in her artificial brain. But what if I told you that you can combine the best of both worlds and actually get ChatGPT to work with Siri?

<p align="center"><a href="#"><img src="https://user-images.githubusercontent.com/48920263/228290609-e7348ccc-f87e-4885-90a0-1526f35cb917.png" draggable="false" ondragstart="return false;" alt="IMG show Siri conbined with ChatGPT" title="Siri conbined with ChatGPT" width="590px" /></a></p>

The process for combining ChatGPT with Siri is quite simple, however, it has requirements and links you need, so make sure you have them all before proceeding.<br/><br/>

## Requirements to get ChatGPT to work with Siri

### Get the Shortcut

The integration of ChatGPT into Siri works through a handy shortcut that will run on your iPhone or Mac. As such, it is necessary to download the Apple Shortcuts app. While the shortcut is named "Explain Me", you can always rename it to whatever you prefer. Download the shortcut by clicking the icon below, but don't run it yet. Once downloaded, keep reading.<br/><br/>

<p align="center"><a href="https://www.icloud.com/shortcuts/ba0f8167574a480fbf865844e78bc1ee"><img src="https://user-images.githubusercontent.com/48920263/230475450-3dadf478-7d83-4dd8-8b16-02fcd1e3a7c8.png" draggable="false" ondragstart="return false;" alt="Download Shortcut" title="Download Shortcut" width="590px" /></a></p><br/><br/>

### Create your OpenAI API Key

To successfully use ChatGPT’s services with Siri, you need its API. OpenAI API key can be accessed through your OpenAI account [here][open-ai-account]. Once logged in, you will see the option to “Create new secret key” click on it to generate an API key.<br/><br/>

<p align="center"><a href="#"><img src="https://user-images.githubusercontent.com/48920263/229297852-ea102356-4720-45b0-8db1-04e3d9534e8a.png" draggable="false" ondragstart="return false;" alt="IMG show how to create new secret key" title="Create new secret key" width="590px" /></a></p><br/><br/>

If you do not have an OpenAI account, you can create one [here][open-ai-API] and then visit the above link. Once done, copy the OpenAI API key.<br/><br/>

<p align="center"><a href="#"><img src="https://user-images.githubusercontent.com/48920263/229298228-8ae23ae3-be9d-446a-b2b4-1f6496478e20.png" draggable="false" ondragstart="return false;" alt="IMG show an example of a OpenAI API Key" title="OpenAI API Key" width="590px" /></a></p><br/><br/>

**Note:** Remember that once you copy the key and close the pop-up, you won't be able to view it again. So keep it somewhere safe.
<br/><br/>

## How to set up and use ChatGPT with Siri

### Setting Up

Once you have downloaded the shortcut and copied the API key, it’s time to make it work and see it in action:

1. Open the Shortcuts app to access the downloaded "Explain Me" shortcut.
2. Once the shortcut has been launched, follow the prompts to set where to store your API key. You will be asked to keep it within the shortcut or store it inside Data Jar.
3. The OpenAI API is powered by a diverse set of models with different capabilities and price points. Decide which model version you want to use (by default it uses gpt-3.5-turbo).<br/><br/>

<p align="center"><a href="#"><img src="https://user-images.githubusercontent.com/48920263/230772190-21d386b5-44bb-4b16-890d-36a31344d600.png" draggable="false" ondragstart="return false;" alt="IMG show where paste your OpenAI API key" title="Paste your OpenAI API key here" width="590px" /></a></p><br/><br/>

All done! ChatGPT has now been integrated with Siri. You can launch the Shortcut by tapping it within the app or from the menu bar on your Mac. You can also call it by saying "Hey Siri" followed by "Explain Me" and it will launch ChatGPT. This means that you now have the most potent chatbot as your assistant.<br/><br/>

<p align="center"><a href="#"><img src="https://user-images.githubusercontent.com/48920263/230772896-8ac2dc52-a771-477b-ba2a-2a4ae6e874f0.png" draggable="false" ondragstart="return false;" alt="ChatGPT launched with Siri" title="ChatGPT launched with Siri" width="590px" /></a></p>

<br/>

### Considerations

You may think I've used ChatGPT, but it doesn't seem that great. Well, it turns out lots of people are using it wrong, the trick is to make it answer and not think. A good pattern to follow is to be as specific as possible about the output, a vague input will give you a vague answer. Ask for a clear response and provide a detailed list of things he should avoid. It all makes sense. You can't give a worker fake instructions and expect a good result.<br/><br/>

<p align="center"><a href="#"><img src="https://user-images.githubusercontent.com/48920263/230881124-8e539864-c5c1-4517-84c6-a376bb8f6bb1.png" draggable="false" ondragstart="return false;" alt="Example ChatGPT in use" title="Example ChatGPT in use" width="590px" /></a></p>

<br/>

**Hint:** if you want prompts tailored for any situation, whether it's academic essays, creative writing, or problem-solving, you can ask chatGPT to create prompts that lead to the results you're looking for. Starting with the prompt below, we will then iterate the output to arrive at the prompt that gives us the desired result.

    You, ChatGPT, will be my prompt engineer. We will iterate the prompts you issue to arrive at a prompt that gives me the desired output. The first output you give me will ask what the prompt is about, with a few questions to get us on the right track. Then, once you have an initial understanding of what the prompt is about, you'll provide me with the first iteration. Then you will ask more questions to improve the prompt. We will continue this iterative process until we get to the prompt we need to generate my desired output.
<br/>

>Keep in mind that it may happen that the Shortcut may not work due to the overload with other requests of the OpenAI servers.

<br/><br/>
## Notes

If you downloaded the [DALL·E Shortcut][siri-E] you can combine both by downloading this additional shortcut by clicking on the image below. With this solution, you'll still able to launch them separately

<p align="center"><a href="https://www.icloud.com/shortcuts/69cfa2e9424a49e284e827e5f119c27c"><img src="https://user-images.githubusercontent.com/48920263/231785832-15fb6a05-a19c-4f61-ba28-84ad73666849.png" draggable="false" ondragstart="return false;" alt="Download OpenAI Shortcut" title="Download OpenAI Shortcut" width="590px" /></a></p>

### Resources

- [Shortcuts User Guide][apple-shortcuts-guide]
- [Apple Siri][apple-siri]
- [OpenAI][open-ai]
- [OpenAI Models][open-ai-models]
- [ChatGPT][chaGPT]
- [Data Jar][data-jar]

### Contribution

Please report any issues or bugs to the [issues page][issues]. Suggestions for
improvements are welcome!<br/><br/>

<p align="center"><a href="#"><img src="https://user-images.githubusercontent.com/48920263/113406768-5a164900-93ac-11eb-94a7-09377a52bf53.png" draggable="false" ondragstart="return false;" /></a></p>

<p align="center"><a href="https://nicolodiamante.com" target="_blank"><img src="https://user-images.githubusercontent.com/48920263/113433823-31a84200-93e0-11eb-9ffb-9111b389ef2f.png" draggable="false" ondragstart="return false;" alt="Nicol&#242; Diamante Portfolio" title="Nicol&#242; Diamante" width="11px" /></a></p>

<p align="center"><a href="https://github.com/nicolodiamante/SiriGPT/blob/main/LICENSE.md" target="_blank"><img src="https://user-images.githubusercontent.com/48920263/110947109-06ca5100-8340-11eb-99cf-8d245044b8a3.png" draggable="false" ondragstart="return false;" alt="The MIT License" title="The MIT License (MIT)" width="90px" /></a></p>

<!-- Link labels: -->
[open-ai-account]: https://chat.openai.com/auth/login
[open-ai-API]: https://beta.openai.com/account/api-keys
[open-ai-models]: https://platform.openai.com/docs/models
[siri-E]: https://github.com/nicolodiamante/Siri-E
[apple-shortcuts-guide]: https://support.apple.com/en-gb/guide/shortcuts/apd58d46713f/ios
[apple-siri]: https://www.apple.com/siri/
[open-ai]: https://openai.com
[chaGPT]: https://openai.com/blog/chatgpt
[data-jar]: https://datajar.app
[issues]: https://github.com/nicolodiamante/SiriGPT/issues
