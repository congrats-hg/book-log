# 50-pages-a-day

<br>

```python
material = input("paper or internet? ")
title = input("title of the content? ")

if material == "paper":
  pages = int(input("how many pages? "))
elif material == "internet":
  pages = int(input("press Ctrl+P on that page and tell me the number of pages: "))
  pages = pages // 2

print(f"{title} ({pages})")
```

<br>

| 날짜 | 읽은 것 | 페이지 수 | Takeaways |
|:---:|---:|:---:|:---|
|  |  |  |  |
| 251124 | [OpenAI / Docs / Guides / tools / web-search](https://platform.openai.com/docs/guides/tools-web-search?utm_source=chatgpt.com&api-mode=responses) | 3 |  |
|  | [blog / 📑 YAML 개념 & 문법 마스터 하기](https://inpa.tistory.com/entry/YAML-%F0%9F%93%9A-yaml-%EA%B0%9C%EB%85%90-%EB%AC%B8%EB%B2%95-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0-%F0%9F%92%AF-%EC%B4%9D%EC%A0%95%EB%A6%AC) | 11 |  |
|  | [OpenAI / Docs / Prompting / Overview \~ Prompt Engineering](https://platform.openai.com/docs/guides/prompting) | 11 |  |
|  | [OpenAI / Docs / Prompting / Overview \~ Priority Processing](https://platform.openai.com/docs/guides/latency-optimization) | 11 |  |
|  | [OpenAI / Docs / Cost Optimization / Batch](https://platform.openai.com/docs/guides/batch) | 4 |  |
| 251123 | [OpenAI Cookbook / GPT-5 New Params and Tools](https://cookbook.openai.com/examples/gpt-5/gpt-5_new_params_and_tools) | 10 | - Recommended: __Responses API__ with GPT-5 series of model to get the most performance out of the models <br> - high verbosity → great for hand-offs <br> - Use `from IPython.display import display` for structured output on terminal <br> - CFGs can capture the syntax of most programming languages and, in OpenAI custom tools, serve as contracts that force the model to emit only strings that the grammar accepts. <br> - `reasoning = { "effort": "minimal" },` is useful when only fast, simple answer is needed. default is medium |
