# Mask and Query-Answer Demo

* This repo is a modification on the [MAE repo](https://github.com/facebookresearch/mae).

* This repo is based on [`timm==0.4.5`], is needed to work with PyTorch 1.8.1+ and Python 3.7+.

* !pip3 install timm==0.4.5

* This is a Mask and Query-Answer demo using the pre-trained MAE models. No GPU is needed.

The following table provides the pre-trained MAE checkpoints used in this demo:
<table><tbody>
<!-- START TABLE -->
<!-- TABLE HEADER -->
<th valign="bottom"></th>
<th valign="bottom">ViT-Base</th>
<th valign="bottom">ViT-Large</th>
<th valign="bottom">ViT-Large-GANLoss</th>
<!-- TABLE BODY -->
<tr><td align="left">pre-trained checkpoint</td>
<td align="center"><a href="https://dl.fbaipublicfiles.com/mae/pretrain/mae_pretrain_vit_base.pth">download</a></td>
<td align="center"><a href="https://dl.fbaipublicfiles.com/mae/pretrain/mae_pretrain_vit_large.pth">download</a></td>
<td align="center"><a href="https://dl.fbaipublicfiles.com/mae/visualize/mae_visualize_vit_large_ganloss.pth">download</a></td>
</tr>
</tbody></table>

* The dataset used in this demo is built on ILSVRC2012 dataset's [Val](https://image-net.org/data/ILSVRC/2012/ILSVRC2012_img_val.tar) and [Test](https://image-net.org/data/ILSVRC/2012/ILSVRC2012_img_test_v10102019.tar) set

