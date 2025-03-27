# prj-liner

## Files
- Train: Train set (400 data points)
- Augment: GPT 를 사용하여 train set 에 augmented data 를 더한 set. 총 1600개의 data 가 있음.
- Test: Test set (100 data points)
- GPT_prompt.ipynb: 각 metric 별로 사용한 zero-shot, few-shot prompt 를 포함한 파일
- roberta_(metric).ipynb: 각 metric 별 classifier 를 fine-tune 할때 사용한 코드

## Dataset Details
각 metric 별로 class 의 정의
- Scope: 0 (Depth), 1 (Neutral), 2 (Breadth)
- Role: 0 (Summarizer), 1 (Neutral), 2 (Interpreter)
- Presentation: 0 (Paragraph), 1 (Bullet-point), 2 (Answer-only), 3 (Neutral)
- Tone: 0 (Formal), 1 (Neutral), 2 (Informal)
- Language: 0 (Complex), 1 (Neutral), 2 (Simple)
- Type: 0 (Scholarly), 1 (Neutral), 2 (Popular)
- Recency: 0 (Recent), 1 (Neutral), 2 (Old)
