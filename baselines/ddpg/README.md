# DDPG

- Original paper: https://arxiv.org/abs/1509.02971
- Baselines post: https://blog.openai.com/better-exploration-with-parameter-noise/
- `python3 -m baselines.ddpg.main` runs the algorithm for 1M frames = 10M timesteps on a Mujoco environment. See help (`-h`) for more options.
- If the ROS nodes or Gazebo is not killed when you use ctrl+c call ./kill_all.sh in baselines/baseline/ddpg
