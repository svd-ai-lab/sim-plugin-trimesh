# sim-plugin-trimesh

Trimesh driver for [sim-cli](https://github.com/svd-ai-lab/sim-cli),
distributed as an out-of-tree plugin.

Trimesh driver for sim.

## Install

```bash
sim plugin install trimesh
```

Other paths:

```bash
pip install git+https://github.com/svd-ai-lab/sim-plugin-trimesh@v0.1.0
pip install https://github.com/svd-ai-lab/sim-plugin-trimesh/releases/download/v0.1.0/sim_plugin_trimesh-0.1.0-py3-none-any.whl
pip install -e .
```

After install:

```bash
sim plugin doctor trimesh
sim plugin sync-skills
```

## Development

```bash
git clone https://github.com/svd-ai-lab/sim-plugin-trimesh
cd sim-plugin-trimesh
uv sync
uv run pytest
```

## License

Apache-2.0.
