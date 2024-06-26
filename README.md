- # 1 **项目概述**

  Forest3 专注森林是一个基于区块链技术的去中心化应用（DApp），旨在通过经济激励和社区支持帮助用户提升自律，实现个人目标。

  ## 2 **目标用户群体**

  - 寻求通过经济激励提高自律性的个人用户
  - 对区块链技术和去中心化应用感兴趣的用户
  - 希望与朋友或团队共同设定并实现目标的用户

  ## 3 **功能需求**

  ### **3.1 用户结组与自律基金**

  #### **3.1.1 创建或加入小组**

  - **功能描述**：用户可以创建一个新的小组或加入现有小组。每个小组至少需要4人，最多不超过10人。
  - **技术实现**：利用智能合约管理小组的创建和加入流程，确保群组人数限制。

  #### **3.1.2 设定群组专注目标**

  - **功能描述**：群组创建者可以设定一个或多个专注目标，小组成员需同意目标并缴纳自律基金。
  - **技术实现**：通过智能合约设定目标和押注规则，确保规则的透明和公正。

  ### **3.2 投票验证流程**

  #### **3.2.1 任务提交**

  - **功能描述**：群组成员在完成个人目标后，需要在DApp内提交相应的证明。
  - **技术实现**：用户上传证明至DApp，智能合约记录提交时间。

  #### **3.2.2 投票启动与成员投票**

  - **功能描述**：所有成员提交证明后，DApp启动投票流程，群组成员对每个证明进行审核并投票。
  - **技术实现**：智能合约管理投票流程，记录每位成员的投票。

  #### **3.2.3 投票结果与基金分配**

  - **功能描述**：超过半数投票认为证明有效，则任务完成，智能合约自动分配自律基金。
  - **技术实现**：智能合约根据投票结果和预设规则自动执行基金分配。

  ### **3.3 任务证明上链**

  - **功能描述**：用户完成任务的证明通过区块链上链，确保不可篡改。
  - **技术实现**：智能合约验证证明的有效性，并将结果上链。

  ## **技术架构**

  - **区块链开发**：HardHat。
  - **智能合约开发**：使用Solidity等语言编写智能合约，实现应用的核心逻辑。
  - **前端界面**：使用Next.js构建用户友好的前端界面，与智能合约交互。
