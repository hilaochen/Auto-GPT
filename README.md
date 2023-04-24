# Auto-GPT
Auto-GPT 是一个实验性开源应用程序，展示了 GPT-4 语言模型的功能。该程序由 GPT-4 驱动，将 LLM 的“思想”链接在一起，以自主实现您设定的任何目标。作为 GPT-4 完全自主运行的首批示例之一，Auto-GPT 突破了 AI 的可能性界限。
要安装 Auto-GPT，请按照下列步骤操作：

确保满足上述所有要求，如果没有，请安装/获取它们。
以下命令应在 CMD、Bash 或 Powershell 窗口中执行。为此，请转到计算机上的文件夹，单击顶部的文件夹路径并键入 CMD，然后按 Enter。

克隆存储库：对于此步骤，您需要安装 Git，但您可以通过单击此页面顶部的按钮来下载 zip 文件 ☝️
git clone https://github.com/Torantulino/Auto-GPT.git
导航到项目目录：（将其输入您的 CMD 窗口，您的目标是将 CMD 窗口导航到您刚刚下载的存储库）
cd 'Auto-GPT'
安装所需的依赖项：（同样，将其键入您的 CMD 窗口）
pip install -r requirements.txt
将 .env.template 重命名为 .env 并填写您的 OPENAI_API_KEY。如果您打算使用语音模式，请同时填写您的 ELEVEN_LABS_API_KEY。
从以下网址获取您的 OpenAI API 密钥：https://platform.openai.com/account/api-keys。
从以下网址获取您的 ElevenLabs API 密钥：https://elevenlabs.io。您可以使用网站上的“个人资料”选项卡查看您的 xi-api-key。
如果要在 Azure 实例上使用 GPT，请将 USE_AZURE 设置为 True，然后：
将 azure.yaml.template 重命名为 azure.yaml，并在 azure_model_map 部分提供相关的 azure_api_base、azure_api_version 和相关模型的所有部署 ID：
fast_llm_model_deployment_id - 您的 gpt-3.5-turbo 或 gpt-4 部署 ID
smart_llm_model_deployment_id - 您的 gpt-4 部署 ID
embedding_model_deployment_id - 您的 text-embedding-ada-002 v2 部署 ID
请将所有这些值指定为双引号字符串
详细信息可在此处找到：Microsoft Azure 端点部分中的 https://pypi.org/project/openai/ 和此处：https://learn.microsoft.com/en-us/azure/cognitive-services/openai/tutorials /embeddings?tabs=嵌入模型的命令行。

一个好用的AI工具合集网站
http://www.daokeyou.top/common/ai

![QQ图片20230424083827](https://user-images.githubusercontent.com/16281830/233876516-d8787964-7d5c-40e4-8fd3-7290341f533e.png)

