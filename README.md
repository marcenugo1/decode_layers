

# Exploring the Effects of Outcome of Each Decoder Layer of a Large Language Model for Text Generation 

Goal: Understand the effects of layers on generation. The goal is to identify, as the number of layer progresses, how the generated outcome improves. 

#### Requirements

Instructions to install libraries using *requirements.txt* file.

```shell
cd layers 
pip install -r requirements.txt
```


### Visualization and Evaluation

- torch.ipynb: Visualize and evaluate the probabilities of each token on each layer. Compare how the tokens probabilites fluctuate on each layer. Evaluate Metrics on Layers 8,16,24 and 32. 
- inseq.ipynb: Visualize the generated top tokens guess probabilites accross all given layers. 

### References

- Chuang, Y. S., Xie, Y., Luo, H., Kim, Y., Glass, J., & He, P. (2023). Dola: Decoding by contrasting layers improves factuality in large language models. arXiv preprint arXiv:2309.03883.
- Sarti, Gabriele, Nils Feldhus, Ludwig Sickert, Oskar Van Der Wal, Malvina Nissim, and Arianna Bisazza. "Inseq: An interpretability toolkit for sequence generation models." arXiv preprint arXiv:2302.13942 (2023).

## License
As a free open-source implementation, our repository is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. All other warranties including, but not limited to, merchantability and fitness for purpose, whether express, implied, or arising by operation of law, course of dealing, or trade usage are hereby disclaimed. I believe that the programs compute what I claim they compute, but I do not guarantee this. The programs may be poorly and inconsistently documented and may contain undocumented components, features or modifications. I make no guarantee that these programs will be suitable for any application.

