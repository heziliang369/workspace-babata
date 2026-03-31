# HEARTBEAT.md

# 定时获取成都天气
- cron: "*/2 * * * *"  # 每2分钟执行一次
  command: "weather --city 成都"

# Keep this file empty (or with only comments) to skip heartbeat API calls.

# Add tasks below when you want the agent to check something periodically.
