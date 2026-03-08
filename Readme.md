Q1 VLM如果錯了，能否用推理VLM reasoning知道現在的回覆錯了?或可能是錯的而重新修正?修正是否可以用Function calling介入?是否會提升

Q2 能否用推裡舉一反三知道要怎麼處裡現在的問題或function calling (ex:無法正確辨識三頭肌在哪裡但知道二頭肌跟肩膀之間是三頭肌而標出三頭肌)

Q3 出現內在知識矛盾與外在知識衝突時，能否將衝突說出來然後讓人類知道，把還能再一步判斷的步驟交給人類，不然可能誤導。

可參考Paper


1. https://aclanthology.org/2025.acl-long.82.pdf  (ACL 2025)
<img width="718" height="169" alt="image" src="https://github.com/user-attachments/assets/24c914ac-4910-4786-97ed-a805b18314c1" />

2. https://proceedings.neurips.cc/paper_files/paper/2024/file/3aa291abc426d7a29fb08418c1244177-Paper-Datasets_and_Benchmarks_Track.pdf (NeuIPS 2025)

3.Reasoning Models Struggle to Control their Chains of Thought

https://cdn.openai.com/pdf/a21c39c1-fa07-41db-9078-973a12620117/cot_controllability.pdf

3/8-3/22 試試看VLM相關的Dataset，不一定侷限健身(當然健身很好，是我們本來目標)，視覺辨識輔助文字知識、文字知識輔助視覺，甚至需要一至多輪Reasoning的都是好議題，Dataset可以不用一次跑完，只挑4-5筆都沒關係，文字輸入(出)影像輸出(入)的pair，想一下有沒有這樣的Case，然後用閉源跑看看、也用1-2個開源SOTA跑看看，我們看結果再來討論
