# rag_basic_ex
rag 기본익히기


# 가상환경 셋팅하기
```
- 새로운 가상환경 만들기
conda create -n lc_env python=3.12

- 가상환경 활성화
conda activate lc_env

- jupyter lab 설치
pip install jupyterlab

- 가상환경 jupyter lab에 추가하기
pip install ipykernel
python -m ipykernel install --user --nam lcent

```

# 설치 라이브러리
```
pip install -qU python-dotenv
pip install -qU pandas matplotlib tqdm ipywidgets

pip install -qU pinecone langchain-pinecone
pip install -qU langchain langchain-community langchain-openai

- 허깅페이스 오픈소스 데이터 사용
pip install datasets

```