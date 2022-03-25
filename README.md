# 2022: A Year Full of Amazing AI papers- A Review [WORK IN PROGRESS] 📌
## A curated list of the latest breakthroughs in AI by release date with a clear video explanation, link to a more in-depth article, and code.

While the world is still recovering, research hasn't slowed its frenetic pace, especially in the field of artificial intelligence. More, many important aspects were highlighted this year, like the ethical aspects, important biases, governance, transparency and much more. Artificial intelligence and our understanding of the human brain and its link to AI are constantly evolving, showing promising applications improving our life's quality in the near future. Still, we ought to be careful with which technology we choose to apply.

>"Science cannot tell us what we ought to do, only what we can do."<br/>- Jean-Paul Sartre, Being and Nothingness

Here is a work in progress of the most interesting research papers for 2022. In short, it is curated list of the latest breakthroughs in AI and Data Science by release date with a clear video explanation, link to a more in-depth article, and code (if applicable). Enjoy the read!

**The complete reference to each paper is listed at the end of this repository.** *Star this repository to stay up to date!* ⭐️

Maintainer: [louisfb01](https://github.com/louisfb01)

Subscribe to my [newsletter](http://eepurl.com/huGLT5) - The latest updates in AI explained every week.


*Feel free to [message me](https://www.louisbouchard.ai/contact/) any interesting paper I may have missed to add to this repository.*

*Tag me on **Twitter** [@Whats_AI](https://twitter.com/Whats_AI) or **LinkedIn** [@Louis (What's AI) Bouchard](https://www.linkedin.com/in/whats-ai/) if you share the list!*


👀 **If you'd like to support my work** and use W&B (for free) to track your ML experiments and make your work reproducible or collaborate with a team, you can try it out by following [this guide](https://colab.research.google.com/github/louisfb01/examples/blob/master/colabs/pytorch/Simple_PyTorch_Integration.ipynb)! Since most of the code here is PyTorch-based, we thought that a [QuickStart guide](https://colab.research.google.com/github/louisfb01/examples/blob/master/colabs/pytorch/Simple_PyTorch_Integration.ipynb) for using W&B on PyTorch would be most interesting to share.

👉Follow [this quick guide](https://colab.research.google.com/github/louisfb01/examples/blob/master/colabs/pytorch/Simple_PyTorch_Integration.ipynb), use the same W&B lines in your code or any of the repos below, and have all your experiments automatically tracked in your w&b account! It doesn't take more than 5 minutes to set up and will change your life as it did for me! [Here's a more advanced guide](https://colab.research.google.com/github/louisfb01/examples/blob/master/colabs/pytorch/Organizing_Hyperparameter_Sweeps_in_PyTorch_with_W%26B.ipynb) for using Hyperparameter Sweeps if interested :)

🙌 Thank you to [Weights & Biases](https://wandb.ai/) for sponsoring this repository and the work I've been doing, and thanks to any of you using this link and trying W&B!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/louisfb01/examples/blob/master/colabs/pytorch/Simple_PyTorch_Integration.ipynb)

----

## The Full List
- [Resolution-robust Large Mask Inpainting with Fourier Convolutions [1]](#1)
- [Stitch it in Time: GAN-Based Facial Editing of Real Videos [2]](#2)
- [NeROIC: Neural Rendering of Objects from Online Image Collections [3]](#3)
- [SpeechPainter: Text-conditioned Speech Inpainting [4]](#4)
- [Towards real-world blind face restoration with generative facial prior [5]](#5)
- [4D-Net for Learned Multi-Modal Alignment [6]](#6)
- [Paper references](#references)

---

## Resolution-robust Large Mask Inpainting with Fourier Convolutions [1]<a name="1"></a>
You’ve most certainly experienced this situation once: You take a great picture with your friend, and someone is photobombing behind you, ruining your future Instagram post. Well, that’s no longer an issue. Either it is a person or a trashcan you forgot to remove before taking your selfie that’s ruining your picture. This AI will just automatically remove the undesired object or person in the image and save your post. It’s just like a professional photoshop designer in your pocket, and with a simple click!

This task of removing part of an image and replacing it with what should appear behind has been tackled by many AI researchers for a long time. It is called image inpainting, and it’s extremely challenging...


* Short Video Explanation:<br/>
[<img src="https://imgur.com/d5ClyqP.png" width="512"/>](https://youtu.be/Ia79AvGzveQ)
* Short read: [This AI Removes Unwanted Objects From your Images!](https://www.louisbouchard.ai/lama/)
* Paper: [Resolution-robust Large Mask Inpainting with Fourier Convolutions](https://arxiv.org/pdf/2109.07161.pdf)
* [Code](https://github.com/saic-mdal/lama)
* [Colab Demo](https://colab.research.google.com/github/saic-mdal/lama/blob/master/colab/LaMa_inpainting.ipynb)
* [Product using LaMa](https://cleanup.pictures/)


## Stitch it in Time: GAN-Based Facial Editing of Real Videos [2]<a name="2"></a>
You've most certainly seen movies like the recent Captain Marvel or Gemini Man where Samuel L Jackson and Will Smith appeared to look like they were much younger. This requires hundreds if not thousands of hours of work from professionals manually editing the scenes he appeared in.
Instead, you could use a simple AI and do it within a few minutes. Indeed, many techniques allow you to add smiles, make you look younger or older, all automatically using AI-based algorithms. It is called AI-based face manipulations in videos and here's the current state-of-the-art in 2022!


* Short Video Explanation:<br/>
[<img src="https://imgur.com/lvgMjzS.png" width="512"/>](https://youtu.be/mqItu9XoUgk)
* Short read: [AI Facial Editing of Real Videos ! Stitch it in Time Explained](https://www.louisbouchard.ai/stitch-it-in-time/)
* Paper: [Stitch it in Time: GAN-Based Facial Editing of Real Videos](https://arxiv.org/abs/2201.08361)
* [Code](https://github.com/rotemtzaban/STIT)


## NeROIC: Neural Rendering of Objects from Online Image Collections [3]<a name="3"></a>
Neural Rendering. Neural Rendering is the ability to generate a photorealistic model in space just like this one, from pictures of the object, person, or scene of interest. In this case, you’d have a handful of pictures of this sculpture and ask the machine to understand what the object in these pictures should look like in space. You are basically asking a machine to understand physics and shapes out of images. This is quite easy for us since we only know the real world and depths, but it’s a whole other challenge for a machine that only sees pixels.
It’s great that the generated model looks accurate with realistic shapes, but what about how it blends in the new scene? And what if the lighting conditions vary in the pictures taken and the generated model looks different depending on the angle you look at it? This would automatically seem weird and unrealistic to us. These are the challenges Snapchat and the University of Southern California attacked in this new research.


* Short Video Explanation:<br/>
[<img src="https://imgur.com/xTpuwcN.png" width="512"/>](https://youtu.be/88Pl9zD1Z78)
* Short read: [Create Realistic 3D Renderings with AI !](https://www.louisbouchard.ai/neroic/)
* Paper: [NeROIC: Neural Rendering of Objects from Online Image Collections](https://arxiv.org/pdf/2201.02533.pdf)
* [Code](https://github.com/snap-research/NeROIC)


## SpeechPainter: Text-conditioned Speech Inpainting [4]<a name="4"></a>
We’ve seen image inpainting, which aims to remove an undesirable object from a picture. The machine learning-based techniques do not simply remove the objects, but they also understand the picture and fill the missing parts of the image with what the background should look like.
The recent advancements are incredible, just like the results, and this inpainting task can be quite useful for many applications like advertisements or improving your future Instagram post. We also covered an even more challenging task: video inpainting, where the same process is applied to videos to remove objects or people.

The challenge with videos comes with staying consistent from frame to frame without any buggy artifacts. But now, what happens if we correctly remove a person from a movie and the sound is still there, unchanged? Well, we may hear a ghost and ruin all our work.

This is where a task I never covered on my channel comes in: speech inpainting. You heard it right, researchers from Google just published a paper aiming at inpainting speech, and, as we will see, the results are quite impressive. Okay, we might rather hear than see the results, but you get the point. It can correct your grammar, pronunciation or even remove background noise. All things I definitely need to keep working on, or… simply use their new model… Listen to the examples in my video!


* Short Video Explanation:<br/>
[<img src="https://imgur.com/JyQ41Qv.png" width="512"/>](https://youtu.be/zIIc4bRf5Hg)
* Short read: [Speech Inpainting with AI !](https://www.louisbouchard.ai/speech-inpainting-with-ai/)
* Paper: [SpeechPainter: Text-conditioned Speech Inpainting](https://arxiv.org/pdf/2202.07273.pdf)
* [Listen to more examples](https://google-research.github.io/seanet/speechpainter/examples/)


## Towards real-world blind face restoration with generative facial prior [5]<a name="5"></a>
Do you also have old pictures of yourself or close ones that didn’t age well or that you, or your parents, took before we could produce high-quality images? I do, and I felt like those memories were damaged forever. Boy, was I wrong!

This new and completely free AI model can fix most of your old pictures in a split second. It works well even with very low or high-quality inputs, which is typically quite the challenge.

This week’s paper called Towards Real-World Blind Face Restoration with Generative Facial Prior tackles the photo restoration task with outstanding results. What’s even cooler is that you can try it yourself and in your preferred way. They have open-sourced their code, created a demo and online applications for you to try right now. If the results you’ve seen above aren’t convincing enough, just watch the video and let me know what you think in the comments, I know it will blow your mind!


* Short Video Explanation:<br/>
[<img src="https://imgur.com/DxxFRLI.png" width="512"/>](https://youtu.be/nLDVtzcSeqM)
* Short read: [Impressive photo restoration by AI !](https://www.louisbouchard.ai/gfp-gan/)
* Paper: [Towards real-world blind face restoration with generative facial prior](https://arxiv.org/pdf/2101.04061.pdf)
* [Code](https://github.com/TencentARC/GFPGAN)
* [Colab Demo](https://colab.research.google.com/drive/1sVsoBd9AjckIXThgtZhGrHRfFI6UUYOo)
* [Online app](https://huggingface.co/spaces/akhaliq/GFPGAN)


## 4D-Net for Learned Multi-Modal Alignment [6]<a name="6"></a>
How do autonomous vehicles see?

You’ve probably heard of LiDAR sensors or other weird cameras they are using. But how do they work, how can they see the world, and what do they see exactly compared to us? Understanding how they work is essential if we want to put them on the road, primarily if you work in the government or build the next regulations. But also as a client of these services.

We previously covered how Tesla autopilot sees and works, but they are different from conventional autonomous vehicles. Tesla only uses cameras to understand the world, while most of them, like Waymo, use regular cameras and 3D LiDAR sensors. These LiDAR sensors are pretty simple to understand: they won’t produce images like regular cameras but 3D point clouds. LiDAR cameras measure the distance between objects, calculating the pulse laser’s traveling time that they project to the object.

Still, how can we efficiently combine this information and have the vehicle understand it? And what does the vehicle end up seeing? Only points everywhere? Is it enough for driving on our roads? We will look into this with a new research paper by Waymo and Google Research...


* Short Video Explanation:<br/>
[<img src="https://imgur.com/AxGLy7p.png" width="512"/>](https://youtu.be/0nJMnw1Ldks)
* Short read: [Combine Lidar and Cameras for 3D object detection - Waymo](https://www.louisbouchard.ai/waymo-lidar/)
* Paper: [4D-Net for Learned Multi-Modal Alignment](https://openaccess.thecvf.com/content/ICCV2021/papers/Piergiovanni_4D-Net_for_Learned_Multi-Modal_Alignment_ICCV_2021_paper.pdf)


---


>If you would like to read more papers and have a broader view, here is another great repository for you covering 2021:
[2021: A Year Full of Amazing AI papers- A Review](https://github.com/louisfb01/best_AI_papers_2021) and feel free to subscribe to my weekly [newsletter](http://eepurl.com/huGLT5) and stay up-to-date with new publications in AI for 2022!


*Tag me on **Twitter** [@Whats_AI](https://twitter.com/Whats_AI) or **LinkedIn** [@Louis (What's AI) Bouchard](https://www.linkedin.com/in/whats-ai/) if you share the list!*

---

## Paper references<a name="references"></a>

[1] Suvorov, R., Logacheva, E., Mashikhin, A., Remizova, A., Ashukha, A., Silvestrov, A., Kong, N., Goka, H., Park, K. and Lempitsky, V., 2022. Resolution-robust Large Mask Inpainting with Fourier Convolutions. In Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (pp. 2149–2159)., https://arxiv.org/pdf/2109.07161.pdf

[2] Tzaban, R., Mokady, R., Gal, R., Bermano, A.H. and Cohen-Or, D., 2022. Stitch it in Time: GAN-Based Facial Editing of Real Videos. https://arxiv.org/abs/2201.08361

[3] Kuang, Z., Olszewski, K., Chai, M., Huang, Z., Achlioptas, P. and Tulyakov, S., 2022. NeROIC: Neural Rendering of Objects from Online Image Collections. https://arxiv.org/pdf/2201.02533.pdf

[4] Borsos, Z., Sharifi, M. and Tagliasacchi, M., 2022. SpeechPainter: Text-conditioned Speech Inpainting. https://arxiv.org/pdf/2202.07273.pdf

[5] Wang, X., Li, Y., Zhang, H. and Shan, Y., 2021. Towards real-world blind face restoration with generative facial prior. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 9168–9178), https://arxiv.org/pdf/2101.04061.pdf

[6] Piergiovanni, A.J., Casser, V., Ryoo, M.S. and Angelova, A., 2021. 4d-net for learned multi-modal alignment. In Proceedings of the IEEE/CVF International Conference on Computer Vision (pp. 15435–15445), https://openaccess.thecvf.com/content/ICCV2021/papers/Piergiovanni_4D-Net_for_Learned_Multi-Modal_Alignment_ICCV_2021_paper.pdf.
