## BLMM Crystal Transformer

Machine Learning and Evolution Laboratory <break>
Department of Computer Science and Engineering<break>
University of South Carolina


How to cite:

Lai Wei, Qinyang Li, Yuqi Song, Stanislav Stefanov, Edirisuriya M. D. Siriwardane, Jianjun Hu*. Crystal Transformer: Self-learning neural language model for Generative and Tinkering Design of Materials. Arxiv. 2022


## Datasets

[OQMD-mix, MP-mix, ICSD-mix datasets](https://doi.org/10.6084/m9.figshare.19495100)

[OQMD-pure, ICSD-pure, MP-pure](https://doi.org/10.6084/m9.figshare.19495064)

## Trained Models




## How to run the generators

    python test.py --no_cuda --root_dir model_pure --checkpoint model_pure/471_model.ckpt \
      --fill test2.blank  --decode greedy --output ./test.tsf

test2.blank file:

    <blank> Ti O O O

## BLMM Tinker Web app for materials doping

[http://www.materialsatlas.org/blmtinker](http://www.materialsatlas.org/blmtinker)
