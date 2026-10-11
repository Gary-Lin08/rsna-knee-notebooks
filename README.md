# RSNA Knee notebooks

集中保存本项目现有的 Jupyter / Kaggle notebooks，便于代码审查、预处理对比和协作。

## 范围与处理

- 收集自项目目录与 `D:/rsna-knee` 存档，共 **34 个 notebooks**。
- 保留代码、Markdown、原文件名与版本；文件名前缀及 `--` 标记原目录结构，避免同名覆盖。
- 上传副本已清除运行输出、执行计数与非必要元数据；原文件未修改。
- `manifest.json` 记录来源相对路径、原始及上传 SHA-256。
- 部分文件是从第三方公开项目 / Kaggle 拉取的参考，原作者权利及许可继续适用；本集合不添加统一代码许可。仅收集不代表资格、正确性或得分已审计通过。
- 仅含 notebooks 与目录说明；不包含 MRI 数据、患者影像、权重、账号凭据或本地日志。

## 使用

多数 notebook 依赖 Kaggle `/kaggle/input` 数据集、指定模型资产或当地脚本。这个仓库是现有源码档案，并非统一的一键运行环境。运行前检查各 notebook 的路径、依赖与数据挂载。脚本型 Kaggle kernels 不属于 `.ipynb`，未转换或伪装成 notebook。

项目交接记录最后核验公开分为 0.949，目标为本账号 COMPLETE 公开榜 >=0.953 且审计通过；本次归档没有运行实验或提交。

## Notebook 索引

| 文件 | 原目录（相对） | Cells |
| --- | --- | --- |
| [project--references--rsna-knee-abnormalities-efficiency-lb.ipynb](project--references--rsna-knee-abnormalities-efficiency-lb.ipynb) | `project/references/rsna-knee-abnormalities-efficiency-lb.ipynb` | 2 |
| [archive--analysis--public_latest_audit--rsna-knee-fast-2xt4-inference.ipynb](archive--analysis--public_latest_audit--rsna-knee-fast-2xt4-inference.ipynb) | `archive/analysis/public_latest_audit/rsna-knee-fast-2xt4-inference.ipynb` | 30 |
| [archive--analysis--radclip_audit--CLIP_Finetuning.ipynb](archive--analysis--radclip_audit--CLIP_Finetuning.ipynb) | `archive/analysis/radclip_audit/CLIP_Finetuning.ipynb` | 22 |
| [archive--analysis--radclip_audit--RadCLIP_Inference_Example_VQA.ipynb](archive--analysis--radclip_audit--RadCLIP_Inference_Example_VQA.ipynb) | `archive/analysis/radclip_audit/RadCLIP_Inference_Example_VQA.ipynb` | 17 |
| [archive--analysis--radimagenet_audit--pytorch_example.ipynb](archive--analysis--radimagenet_audit--pytorch_example.ipynb) | `archive/analysis/radimagenet_audit/pytorch_example.ipynb` | 17 |
| [archive--analysis--submission_audit--fork_plus_latest--rsna-knee-fast-2xt4-raptor44.ipynb](archive--analysis--submission_audit--fork_plus_latest--rsna-knee-fast-2xt4-raptor44.ipynb) | `archive/analysis/submission_audit/fork_plus_latest/rsna-knee-fast-2xt4-raptor44.ipynb` | 31 |
| [archive--analysis--submission_audit--fork_plus_latest--v3_source_confirm--rsna-knee-fast-2xt4-raptor44.ipynb](archive--analysis--submission_audit--fork_plus_latest--v3_source_confirm--rsna-knee-fast-2xt4-raptor44.ipynb) | `archive/analysis/submission_audit/fork_plus_latest/v3_source_confirm/rsna-knee-fast-2xt4-raptor44.ipynb` | 31 |
| [archive--kaggle_submit_kernel--remote--rsna-knee-coat64-fast-swa-submit-notebook.ipynb](archive--kaggle_submit_kernel--remote--rsna-knee-coat64-fast-swa-submit-notebook.ipynb) | `archive/kaggle_submit_kernel/remote/rsna-knee-coat64-fast-swa-submit-notebook.ipynb` | 2 |
| [archive--kaggle_submit_kernel--submit.ipynb](archive--kaggle_submit_kernel--submit.ipynb) | `archive/kaggle_submit_kernel/submit.ipynb` | 2 |
| [archive--kagglehub--datasets--laymond--rsna-knee-abnormality-qwen3-8b-weak-labels--versions--2--Qwen2.5-32BGenerator.ipynb](archive--kagglehub--datasets--laymond--rsna-knee-abnormality-qwen3-8b-weak-labels--versions--2--Qwen2.5-32BGenerator.ipynb) | `archive/kagglehub/datasets/laymond/rsna-knee-abnormality-qwen3-8b-weak-labels/versions/2/Qwen2.5-32BGenerator.ipynb` | 17 |
| [archive--kagglehub--datasets--laymond--rsna-knee-abnormality-qwen3-8b-weak-labels--versions--2--Qwen3-8BGenerator.ipynb](archive--kagglehub--datasets--laymond--rsna-knee-abnormality-qwen3-8b-weak-labels--versions--2--Qwen3-8BGenerator.ipynb) | `archive/kagglehub/datasets/laymond/rsna-knee-abnormality-qwen3-8b-weak-labels/versions/2/Qwen3-8BGenerator.ipynb` | 21 |
| [archive--kernels--fork--rsna-knee-fast-2xt4-inference.ipynb](archive--kernels--fork--rsna-knee-fast-2xt4-inference.ipynb) | `archive/kernels/fork/rsna-knee-fast-2xt4-inference.ipynb` | 30 |
| [archive--kernels--knee-anatomical-public--kernel.ipynb](archive--kernels--knee-anatomical-public--kernel.ipynb) | `archive/kernels/knee-anatomical-public/kernel.ipynb` | 5 |
| [archive--kernels--knee-public-mix5-w20--rsna-knee-fast-2xt4-inference.ipynb](archive--kernels--knee-public-mix5-w20--rsna-knee-fast-2xt4-inference.ipynb) | `archive/kernels/knee-public-mix5-w20/rsna-knee-fast-2xt4-inference.ipynb` | 31 |
| [archive--kernels--knee-public-mix5-w20--v3_source_confirm--knee-public-mix5-w20.ipynb](archive--kernels--knee-public-mix5-w20--v3_source_confirm--knee-public-mix5-w20.ipynb) | `archive/kernels/knee-public-mix5-w20/v3_source_confirm/knee-public-mix5-w20.ipynb` | 31 |
| [archive--kernels--knee-public-triple--kernel.ipynb](archive--kernels--knee-public-triple--kernel.ipynb) | `archive/kernels/knee-public-triple/kernel.ipynb` | 8 |
| [archive--kernels--pulled-candidate--rsna-knee-fast-2xt4-raptor44.ipynb](archive--kernels--pulled-candidate--rsna-knee-fast-2xt4-raptor44.ipynb) | `archive/kernels/pulled-candidate/rsna-knee-fast-2xt4-raptor44.ipynb` | 31 |
| [archive--kernels--rsna-knee-fast-2xt4-raptor44--rsna-knee-fast-2xt4-inference.ipynb](archive--kernels--rsna-knee-fast-2xt4-raptor44--rsna-knee-fast-2xt4-inference.ipynb) | `archive/kernels/rsna-knee-fast-2xt4-raptor44/rsna-knee-fast-2xt4-inference.ipynb` | 31 |
| [archive--research--public_refresh--20261010--hitarthjain0--kernel.ipynb](archive--research--public_refresh--20261010--hitarthjain0--kernel.ipynb) | `archive/research/public_refresh/20261010/hitarthjain0/kernel.ipynb` | 11 |
| [archive--research--public_refresh--20261010--nartaa--kernel.ipynb](archive--research--public_refresh--20261010--nartaa--kernel.ipynb) | `archive/research/public_refresh/20261010/nartaa/kernel.ipynb` | 5 |
| [archive--research--public_refresh--20261010--samanyu1808--kernel.ipynb](archive--research--public_refresh--20261010--samanyu1808--kernel.ipynb) | `archive/research/public_refresh/20261010/samanyu1808/kernel.ipynb` | 11 |
| [archive--research--public_refresh--anatomical--rsna-knee-0949-anatomical-mirror.ipynb](archive--research--public_refresh--anatomical--rsna-knee-0949-anatomical-mirror.ipynb) | `archive/research/public_refresh/anatomical/rsna-knee-0949-anatomical-mirror.ipynb` | 5 |
| [archive--research--public_refresh--audit0--rsna-knee-template.ipynb](archive--research--public_refresh--audit0--rsna-knee-template.ipynb) | `archive/research/public_refresh/audit0/rsna-knee-template.ipynb` | 3 |
| [archive--research--public_refresh--audit1--rsna-knee-apex-grandmaster-stack.ipynb](archive--research--public_refresh--audit1--rsna-knee-apex-grandmaster-stack.ipynb) | `archive/research/public_refresh/audit1/rsna-knee-apex-grandmaster-stack.ipynb` | 10 |
| [archive--research--public_refresh--audit2--rsna-knee-v2-velciraptor-dinosaur-speed.ipynb](archive--research--public_refresh--audit2--rsna-knee-v2-velciraptor-dinosaur-speed.ipynb) | `archive/research/public_refresh/audit2/rsna-knee-v2-velciraptor-dinosaur-speed.ipynb` | 5 |
| [archive--research--public_refresh--bees--the-bee-s-knees-final-rsna-push.ipynb](archive--research--public_refresh--bees--the-bee-s-knees-final-rsna-push.ipynb) | `archive/research/public_refresh/bees/the-bee-s-knees-final-rsna-push.ipynb` | 140 |
| [archive--research--public_refresh--dinosaur5--rsna-knee-dinosaur-v5.ipynb](archive--research--public_refresh--dinosaur5--rsna-knee-dinosaur-v5.ipynb) | `archive/research/public_refresh/dinosaur5/rsna-knee-dinosaur-v5.ipynb` | 11 |
| [archive--research--public_refresh--dual951--rsna-knee-sota-dual-engine-stack-lb-0-951.ipynb](archive--research--public_refresh--dual951--rsna-knee-sota-dual-engine-stack-lb-0-951.ipynb) | `archive/research/public_refresh/dual951/rsna-knee-sota-dual-engine-stack-lb-0-951.ipynb` | 11 |
| [archive--research--public_refresh--efficient224--rsna-knee-0945-efficient-224crop.ipynb](archive--research--public_refresh--efficient224--rsna-knee-0945-efficient-224crop.ipynb) | `archive/research/public_refresh/efficient224/rsna-knee-0945-efficient-224crop.ipynb` | 5 |
| [archive--research--public_refresh--helios--rsna-knee-abnormality-detection.ipynb](archive--research--public_refresh--helios--rsna-knee-abnormality-detection.ipynb) | `archive/research/public_refresh/helios/rsna-knee-abnormality-detection.ipynb` | 7 |
| [archive--research--public_refresh--helios_gold--rsna-knee-blend-gold.ipynb](archive--research--public_refresh--helios_gold--rsna-knee-blend-gold.ipynb) | `archive/research/public_refresh/helios_gold/rsna-knee-blend-gold.ipynb` | 7 |
| [archive--research--public_refresh--rabari95--rsna-knee-lb-0-95.ipynb](archive--research--public_refresh--rabari95--rsna-knee-lb-0-95.ipynb) | `archive/research/public_refresh/rabari95/rsna-knee-lb-0-95.ipynb` | 14 |
| [archive--research--public_refresh--reader_blend--rsna-knee-0-949-coatnet-stack-blend-lb-0-949.ipynb](archive--research--public_refresh--reader_blend--rsna-knee-0-949-coatnet-stack-blend-lb-0-949.ipynb) | `archive/research/public_refresh/reader_blend/rsna-knee-0-949-coatnet-stack-blend-lb-0-949.ipynb` | 36 |
| [archive--research--public_refresh--versia7--rsna-versia-7.ipynb](archive--research--public_refresh--versia7--rsna-versia-7.ipynb) | `archive/research/public_refresh/versia7/rsna-versia-7.ipynb` | 15 |
