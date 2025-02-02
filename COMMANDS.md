# Run from cli
```
python llava/serve/cli.py --image-file /Users/akur/projects/LLaVA-Med/data/pmc_articles/PMC6149739/molecules-22-02279-g001.jpg
```

# serve model worker from readme
```
python -m llava.serve.model_worker --host 0.0.0.0 --controller http://localhost:10000 --port 40000 --worker http://localhost:40000 --model-path microsoft/llava-med-v1.5-mistral-7b --multi-modal
```