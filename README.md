# 魚の群泳における極性ネマチック状態を考慮した統合情報量の算出

## フォルダ構成
- code
  - CalculateNematic_Phi_MI.ipynb
    >#極性ネマチック状態を考慮した統合情報量と相互情報量の算出
    #author:wakabayashi
    #condition：5匹，極性ネマチック式のε=0.3のとき
    #data：2019/12/05
    #attention:データや条件は目的に応じて変えましょう．

  - EasyInteractionRaw_Phi.ipynb
    >#単純な３つの相互作用を考慮した統合情報量の算出
    #author:wakabayashi
    #condition：5匹
    #data：2019/1/5
    #attention:データや条件は目的に応じて変えましょう．
    
- data//魚の軌跡データ
  - rawdata
  - movingaverage//30fpsで撮影した動画の5フレームの移動平均を取った結果の一部(コードはまた載せれたら載せます)
- results
    - Fig.3.3: Relationship between the number of fish and Φ. Φ is the average of two samples. Whenε=0.3, Φincreases in phase transition between 5 and 6 individuals.については，CalculateNematic_Phi_MI.ipynbで変数を変えてそれぞれ算出したΦの値をグラフ化した．
    - Fig.3.4: The heat map shows Φ. Each axis corresponds to a different parameter : Distance (mm), Field of View(π(rad)) and Turning Rate (π(rad)).については，EasyInteractionRaw_Phi.ipynbで変数を変えてそれぞれグラフ化した．
     - Fig.3.5: Relationship between the number of fish and MI. MI is the average of two samples. The standarddeviation of MI is 0 except when the number of fish is two. MI increases with fish population.については，CalculateNematic_Phi_MI.ipynbで変数を変えてそれぞれ算出したΦの値をグラフ化した．
     - Fig.3.6: Relationship between MI and Φ due to the changes in population whenε= 0.3. MI is always higherthan Φについては，Fig.3.3とFig.3.5の結果の一部を使用してグラフを作成した．
 
- thesis
- workspace//その他色々
