# State_Space_Model
状態空間モデルにおける以下の3つの問題に対するアルゴリズム  
・欠損値補完  
・長期予測  
・対数尤度の計算  

# 環境の初期設定
python -m venv .venv  //エラーが出るかも, その場合は無視で
.venv\Scripts\Activate  
pip install -r requirements.txt  

# 仮想環境におけるライブラリのインストール手順(powershell)
python -m venv .venv  
.venv\Scripts\Activate  
pip install numpy pandas matplotlib  

pip freeze > requirements.  