<!--
 * @Author: Clover 304363641@qq.com
 * @Date: 2022-07-24 16:02:20
 * @LastEditors: Clover 304363641@qq.com
 * @LastEditTime: 2023-12-01 11:53:12
 * @FilePath: \storyline-generator\README.md
 * @Description: 
 * 
 * Copyright (c) 2023 by ${git_name_email}, All Rights Reserved. 
-->
# storyline-generater

This is the source code for paper *StoryExplorer: A Visualization Framework for Storyline Generation of Textual Narratives.*

![fig_dataVis](https://github.com/Clover-yee/StoryExplorer/blob/v3.0/public/img/teaser.png)

> [**StoryExplorer: A Visualization Framework for Storyline Generation of Textual Narratives**]
> 
> Li Ye, Lei Wang, Shaolun Ruan, Yuwei Meng, Yigang Wang, Wei Chen and Zhiguang Zhou



## Abstract
In the context of the exponentially increasing volume of narrative texts such as novels and news, readers struggle to extract and consistently remember storyline from these intricate texts due to the constraints of human working memory and attention span. To tackle this issue, we propose a visualization approach StoryExplorer, which facilitates the process of knowledge externalization of narrative texts and further makes the form of mental models more coherent. Through the formative study and close collaboration with 2 domain experts, we identified key challenges for the extraction of the storyline. Guided by the distilled requirements, we then propose a set of workflow (i.e., insight finding-scripting-storytelling) to enable users to interactively generate fragments of narrative structures. We then propose a visualization system StoryExplorer which combines stroke annotation and GPT-based visual hints to quickly extract story fragments and interactively construct storyline. To evaluate the effectiveness and usefulness of StoryExplorer, we conducted 2 case studies and in-depth user interviews with 12 target users. The result shows that users can better extract the storyline by using StoryExplorer along with the proposed workflow.

## Install
1. install `npm install`
2. `npm run serve` to run this application
3. `cd server-mongdb` and `node index` to run the server

## ToDo
- [ ] Improve the user interface:
    - [ ] Enable online edit mode
    - [ ] Add support panel function
- [ ] Release more cases data
- [ ] Release the system pipeline
- [ ] Better document the code

## Prompt
