# LLaMA-3.1-fine-tuning-with-financial-QA-dataset

재정데이터_fine_tuning.ipynb:

  - Unsloth에서 제공한 튜토리얼 코드와 재정 정보 질의응답 데이터셋을 활용해 LLaMA 3.1 모델 Fine-tuning 진행
  - 학습된 모델은 GGUF 형식으로 허깅페이스에 저장
  
재정데이터_질의응답_llm_비교.ipynb:

  - Fine-tuning 된 LLaMA 3.1 모델과 학습되지 않은 Vanila LLaMA 3.1 모델의 성능을 정성적으로 비교
  - Fine-tuning을 진행한 후 답변 품질 향상되었으나 정답이 되는 답변을 출력하는 빈도가 매우 낮음 (Hallucination 문제 존재)
  - 향후 RAG 시스템을 추가하여 PDF 파일을 레퍼런스 삼아 답변할 수 있도록 업데이트할 예정
