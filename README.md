# FEVER 2018 Model from Team Papelo, NEC Laboratories America

This is the model file for the [NEC Labs America](http://www.nec-labs.com) Team Papelo [FEVER 2018 system](https://www.github.com/necla-ml/fever2018) for Fact Extraction and Verification, for the [FEVER shared task at EMNLP](http://fever.ai).  Please cite our [system description paper](http://aclweb.org/anthology/W18-5517) from the EMNLP workshop:

```
@inproceedings{malon2018,
  title={Team Papelo: Transformer Networks at FEVER},
  author={Christopher Malon},
  booktitle={Proceedings of the EMNLP First Workshop on Fact Extraction and Verification},
  year={2018}
}
```

## Usage

Because of Github's maximum file size, the model file has been
split into pieces.  To recover it, use

```
cat best_params.all-title-one-r55.jl.a? >best_params.all-title-one-r55.jl
```

The resulting model can be used by the predict script in
[finetune-transformer-lm](https://github.com/cdmalon/finetune-transformer-lm).

