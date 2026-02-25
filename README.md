# ros-go-olym – Government Olympia Layout

`ros-go-olym` là snapshot của Government Olympia (GO) ở tầng **Normative**, dùng để:

- Công bố constitutional canon cho ROS
- Định nghĩa chuẩn kỹ thuật (standards & specs)
- Cung cấp governance/knowledge cho các runtime HA/CO/HO

Không chứa:

- Runtime code
- Private runtime keys
- Execution engine

## Cấu trúc chính

- `c/` – Constitutional canon (authority law, ROS-level hiến pháp)
- `g/` – Governance instruments (policy, charter, rule, stage)
- `s/` – Standards & Specifications (machine-binding standards, envelope/hash/federation)
- `k/` – Knowledge canon (blueprint, stage model, domain knowledge)
- `x/` – Extensions (non-core, experimental, interop)
- `release/` – Sealed bundles (snapshot versioned, immutable)
- `meta/` – Meta-governance (governance model, amendment, compatibility)

Điểm vào chuẩn cho AIA Cogen:

- `olym-structure-rule.ail` – mô tả đầy đủ layout và vai trò từng nhánh
- `c/ros/*` – ROS constitutional canon (authority boundary, 3-space architecture, master canon list)
