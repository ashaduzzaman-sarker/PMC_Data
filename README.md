# PMC Data Pipeline

*A pipeline to construct millions of image-caption figures from PubMed.*

[[NEJM AI Article](https://ai.nejm.org/stoken/default+domain/9VPKUGJYJ5BPFXY83IBS/full?redirectUri=doi/full/10.1056/AIoa2400640)] 

For a hands-on demonstration, refer to the [example notebook](run_pmc15_pipeline.ipynb).


## Environment Setup 

```bash
# it is recmmended to use a virtual environment but not required
python -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt
```

## Reference
```bibtex
@article{zhang2024biomedclip,
  title={A Multimodal Biomedical Foundation Model Trained from Fifteen Million Image–Text Pairs},
  author={Sheng Zhang and Yanbo Xu and Naoto Usuyama and Hanwen Xu and Jaspreet Bagga and Robert Tinn and Sam Preston and Rajesh Rao and Mu Wei and Naveen Valluri and Cliff Wong and Andrea Tupini and Yu Wang and Matt Mazzola and Swadheen Shukla and Lars Liden and Jianfeng Gao and Angela Crabtree and Brian Piening and Carlo Bifulco and Matthew P. Lungren and Tristan Naumann and Sheng Wang and Hoifung Poon},
  journal={NEJM AI},
  year={2024},
  volume={2},
  number={1},
  doi={10.1056/AIoa2400640},
  url={https://ai.nejm.org/doi/full/10.1056/AIoa2400640}
}
```

