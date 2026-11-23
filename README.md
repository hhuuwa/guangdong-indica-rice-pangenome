# 广东籼稻泛基因组

Guangdong indica rice pangenome (*Oryza sativa*).

本数据集包含广东籼稻泛基因组的参考序列、基因组注释，以及对应的编码序列和蛋白质序列。

## 文件清单

| 文件 | 格式 | 内容 |
| --- | --- | --- |
| `pan.fa` | FASTA | 泛基因组参考序列 |
| `pan.V1.gff3` | GFF3 | 泛基因组 V1 注释 |
| `pan.CDS.V1.fa` | FASTA | V1 编码序列（CDS） |
| `pan.pep.V1.fa` | FASTA | V1 蛋白质序列 |

## 下载与解压

从 [GitHub Release v1](https://github.com/hhuuwa/guangdong-indica-rice-pangenome/releases/tag/v1) 下载压缩包 `guangdong-indica-rice-pangenome-v1.tar.gz` 和同名的 `.sha256` 校验文件。在下载目录运行以下命令，校验压缩包后解压。

```bash
shasum -a 256 -c guangdong-indica-rice-pangenome-v1.tar.gz.sha256 && \
  tar -xzf guangdong-indica-rice-pangenome-v1.tar.gz
```
