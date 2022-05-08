# comp4901q_project
MS-G3D-master folder is forked from https://github.com/kenziyuliu/MS-G3D.
- `main.py`: Distributed Data Parallel & Automatic Mixed Precision implementation
- `main_dp.py`: Data Parallel implementation from the MS-G3D paper
- `main_zerp.py`: Distributed Data Parallel & Automatic Mixed Precision & Zero Redundancy optimizer implementation

You can launch the DDP by for example
`python -m torch.distributed.launch --nproc_per_node=4 main.py --config config/nturgbd-cross-subject/train_bone.yaml`
