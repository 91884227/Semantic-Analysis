# Semantic-Analysis
108-1 DS HW4

直接執行model.ipynb即可
產生的答案為 answer.csv

若要預測的檔案名稱不為 test.csv
須修改model.ipynb 的第一行 path 改成 "test.csv"

若需要手動設定GPU的名稱不同
需要改這邊的CODE才能執行
os.environ["CUDA_DEVICE_ORDER"]="PCI_BUS_ID"
os.environ["CUDA_VISIBLE_DEVICES"]="1"
