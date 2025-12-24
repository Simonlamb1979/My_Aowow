# Aowow项目需要从World数据库转换的表格列表

> 生成时间: 2025-12-22  
> 项目版本: Aowow (World of Warcraft数据库项目)

---

## 1. 生物相关表格 (Creature)

| 表格名称 | 描述 |
|---------|------|
| `creature_template` | 生物模板主表 |
| `creature_template_locale` | 生物模板本地化数据 |
| `creature_template_resistance` | 生物抗性数据 |
| `creature_template_spell` | 生物法术数据 |
| `creature_classlevelstats` | 生物等级属性数据 |
| `creature_default_trainer` | 默认训练师数据 |
| `creature` | 生物实例数据 |
| `creature_addon` | 生物附加数据 |
| `creature_loot_template` | 生物掉落模板 |
| `creature_queststarter` | 生物任务起始数据 |
| `creature_questender` | 生物任务结束数据 |
| `trainer` | 训练师数据 |
| `trainer_spell` | 训练师法术数据 |
| `instance_encounters` | 副本遭遇数据 |

---

## 2. 物品相关表格 (Items)

| 表格名称 | 描述 |
|---------|------|
| `item_template` | 物品模板主表 |
| `item_template_locale` | 物品模板本地化数据 |
| `item_loot_template` | 物品掉落模板 |
| `item_enchant_proc_data` | 物品附魔触发数据 |
| `itemset` | 物品套装数据 |
| `item_randomenchant` | 物品随机附魔数据 |
| `item_randomproppoints` | 物品随机属性点数 |
| `mail_loot_template` | 邮件物品模板 |
| `disenchant_loot_template` | 分解物品模板 |
| `fishing_loot_template` | 钓鱼物品模板 |
| `skinning_loot_template` | 剥皮物品模板 |
| `milling_loot_template` | 碾磨物品模板 |
| `prospecting_loot_template` | 采矿物品模板 |
| `pickpocketing_loot_template` | 扒窃物品模板 |
| `npc_vendor` | 商人出售物品 |
| `game_event_npc_vendor` | 节日商人出售物品 |

---

## 3. 任务相关表格 (Quests)

| 表格名称 | 描述 |
|---------|------|
| `quest_template` | 任务模板主表 |
| `quest_template_addon` | 任务模板附加数据 |
| `quest_template_locale` | 任务模板本地化数据 |
| `quest_request_items` | 任务请求物品 |
| `quest_request_items_locale` | 任务请求物品本地化 |
| `quest_offer_reward` | 任务奖励数据 |
| `quest_offer_reward_locale` | 任务奖励本地化 |
| `quest_startend` | 任务起始和结束数据 |

---

## 4. 游戏对象相关表格 (Gameobjects)

| 表格名称 | 描述 |
|---------|------|
| `gameobject_template` | 游戏对象模板主表 |
| `gameobject_template_addon` | 游戏对象模板附加数据 |
| `gameobject_template_locale` | 游戏对象模板本地化 |
| `gameobject` | 游戏对象实例数据 |
| `gameobject_loot_template` | 游戏对象掉落模板 |
| `gameobject_questitem` | 游戏对象任务物品 |
| `gameobject_queststarter` | 游戏对象任务起始 |
| `gameobject_questender` | 游戏对象任务结束 |

---

## 5. 法术相关表格 (Spells)

| 表格名称 | 描述 |
|---------|------|
| `spell_ranks` | 法术等级数据 |
| `spell_dbc` | 法术DBC数据 |
| `spell_group` | 法术组数据 |
| `spell_enchant_proc_data` | 法术附魔触发数据 |
| `skill_discovery_template` | 技能发现模板 |
| `trainer_spell` | 训练师法术数据 |

---

## 6. 世界事件相关表格 (Events)

| 表格名称 | 描述 |
|---------|------|
| `game_event` | 游戏事件主表 |
| `game_event_prerequisite` | 游戏事件前置条件 |
| `game_event_seasonal_questrelation` | 季节性任务关系 |
| `game_event_creature_quest` | 事件生物任务 |
| `game_event_gameobject_quest` | 事件游戏对象任务 |

---

## 7. 区域和传送相关表格 (Zones & Teleport)

| 表格名称 | 描述 |
|---------|------|
| `access_requirement` | 进入需求数据 |
| `areatrigger_teleport` | 区域触发传送 |
| `areatrigger_involvedrelation` | 区域触发关联 |
| `areatrigger_scripts` | 区域触发脚本 |
| `areatrigger_tavern` | 区域触发旅店 |
| `waypoints` | 路径点数据 |
| `waypoint_data` | 路径点详细数据 |
| `script_waypoint` | 脚本路径点 |

---

## 8. 玩家创建相关表格 (Player Creation)

| 表格名称 | 描述 |
|---------|------|
| `playercreateinfo_skills` | 玩家创建技能 |
| `playercreateinfo_item` | 玩家创建物品 |

---

## 9. 成就相关表格 (Achievements)

| 表格名称 | 描述 |
|---------|------|
| `achievement_reward` | 成就奖励 |
| `achievement_reward_locale` | 成就奖励本地化 |
| `dbc_achievement` | DBC成就数据 |

---

## 10. 其他重要表格 (Other Important Tables)

| 表格名称 | 描述 |
|---------|------|
| `factions` | 阵营数据 |
| `smart_scripts` | 智能脚本系统 |
| `disables` | 禁用数据 |
| `vehicle_accessory` | 载具配件 |
| `vehicle_accessory_template` | 载具配件模板 |
| `reference_loot_template` | 引用掉落模板 |
| `skill_perfect_item_template` | 完美物品技能模板 |
| `mail_template` | 邮件模板 |
| `spelldifficulty_dbc` | 法术难度DBC数据 |

---

## 11. 特殊功能表格 (Special Feature Tables)

| 表格名称 | 描述 |
|---------|------|
| `titles` | 称号数据 |
| `holidays` | 节日数据 |
| `zones` | 区域数据 |
| `spawns` | 刷新点数据 |
| `source` | 来源数据 |
| `pet` | 宠物数据 |
| `currencies` | 货币数据 |
| `events` | 事件数据 |
| `emotes` | 表情数据 |
| `dungeonmap` | 地下城地图 |
| `declinedword` | 变格词数据 |
| `classes` | 职业数据 |
| `achievementcriteria` | 成就条件 |
| `areatrigger` | 区域触发器 |
| `totemcategory` | 图腾分类 |
| `taxi` | 出租飞行 |
| `talents` | 天赋 |
| `summonproperties` | 召唤属性 |
| `spellvariables` | 法术变量 |
| `spelloverride` | 法术覆盖 |
| `spellrange` | 法术范围 |
| `spellfocusobject` | 法术焦点对象 |
| `skillline` | 技能线 |
| `skilllineability` | 技能线能力 |
| `soundemitter` | 声音发射器 |
| `sounds` | 声音 |
| `races` | 种族 |
| `scalingstatdistribution` | 缩放属性分布 |
| `scalingstatvalues` | 缩放属性值 |
| `shapeshiftforms` | 变形形态 |
| `itemstats` | 物品属性 |
| `itemextendedcost` | 物品扩展成本 |
| `itemlimitcategory` | 物品限制分类 |
| `itemenchantment` | 物品附魔 |
| `itemenchantmentcondition` | 物品附魔条件 |
| `icons` | 图标 |
| `glyphproperties` | 雕文属性 |
| `factions` | 阵营 |
| `lock` | 锁具 |
| `worldmaparea` | 世界地图区域 |

---

## 12. 数据转换说明

这些表格是从World数据库（魔兽世界模拟器数据库）转换到Aowow数据库的核心表格。转换过程包括：

1. **数据提取**：从World数据库中提取相关表格数据
2. **数据处理**：根据Aowow的需求进行数据格式转换和优化
3. **数据导入**：将处理后的数据导入到Aowow数据库中

每个表格都有特定的用途和转换规则，确保Aowow网站能够正确显示和查询魔兽世界的各种游戏数据。

---

## 13. 使用说明

1. 确保您有正确配置的World数据库（如TrinityCore、MaNGOS等）
2. 运行Aowow的数据转换工具，通常位于setup/tools目录下
3. 按照工具提示选择需要转换的表格类型
4. 等待转换完成，检查Aowow数据库中的数据是否正确导入

> **表格总数**: 约100+个核心表格

---

## 14. 可单独执行的命令 (Standalone Commands)

以下命令可用于单独执行特定功能，无需重新运行整个安装流程：
在项目根目录下执行以下命令：

### 1. 地图相关命令

| 命令 | 描述 |
|------|------|
| `php aowow --build=img-maps` | 解压/生成地图文件 |
| `php aowow --build=img-maps --1` | 生成生物和游戏对象刷新点的透明遮罩 |
| `php aowow --build=img-maps --2` | 生成带有子区域高亮的额外区域地图 |
| `php aowow --build=img-maps --3` | 禁用默认的区域地图输出 |

### 2. 区域数据相关命令

| 命令 | 描述 |
|------|------|
| `php aowow --sql=zones` | 生成区域数据（从DBC转换到aowow_zones表） |

### 3. 生物数据相关命令

| 命令 | 描述 |
|------|------|
| `php aowow --sql=creature` | 生成生物数据 |
| `php aowow --sql=creature_loot` | 生成生物掉落数据 |

### 4. 物品数据相关命令

| 命令 | 描述 |
|------|------|
| `php aowow --sql=item` | 生成物品数据 |
| `php aowow --sql=item_loot` | 生成物品掉落数据 |

### 5. 任务数据相关命令

| 命令 | 描述 |
|------|------|
| `php aowow --sql=quest` | 生成任务数据 |
| `php aowow --sql=quest_startend` | 生成任务起始和结束数据 |

### 6. 游戏对象数据相关命令

| 命令 | 描述 |
|------|------|
| `php aowow --sql=gameobject` | 生成游戏对象数据 |
| `php aowow --sql=gameobject_loot` | 生成游戏对象掉落数据 |

### 7. 法术数据相关命令

| 命令 | 描述 |
|------|------|
| `php aowow --sql=spell` | 生成法术数据 |

### 8. 技能数据相关命令

| 命令 | 描述 |
|------|------|
| `php aowow --sql=skill` | 生成技能数据 |

### 9. 声音数据相关命令

| 命令 | 描述 |
|------|------|
| `php aowow --sql=sounds` | 生成声音数据（从DBC转换到数据库） |
| `php aowow --sql=soundemitters` | 生成声音发射器数据 |
| `php aowow --build=soundfiles` | 处理声音文件并移动到目标位置 |

### 10. 其他常用命令

| 命令 | 描述 |
|------|------|
| `php aowow --sql=achievement` | 生成成就数据 |
| `php aowow --sql=faction` | 生成阵营数据 |
| `php aowow --sql=title` | 生成称号数据 |
| `php aowow --sql=worldmap` | 生成世界地图数据 |

### 11. 数据库配置命令

| 命令 | 描述 |
|------|------|
| `php aowow --db` | 重新配置数据库连接 |

### 12. 全部数据生成命令

| 命令 | 描述 |
|------|------|
| `php aowow --sql=all` | 生成所有SQL数据 |
| `php aowow --build=all` | 生成所有图像文件和数据转储 |

---

## 15. 使用示例

1. **只重新生成地图文件**：
   ```bash
   cd J:\wamp64\www
   php aowow --build=img-maps
   ```

2. **只重新生成区域数据**：
   ```bash
   cd J:\wamp64\www
   php aowow --sql=zones
   ```

3. **生成带有子区域高亮的地图**：
   ```bash
   cd J:\wamp64\www
   php aowow --build=img-maps --2
   ```

4. **重新生成声音数据**：
   ```bash
   cd J:\wamp64\www
   php aowow --sql=sounds
   php aowow --build=soundfiles
   ```

5. **重新配置数据库连接**：
   ```bash
   cd J:\wamp64\www
   php aowow --db
   ```

---

## 16. 注意事项

1. 执行这些命令前，请确保已正确配置数据库连接
2. 某些命令可能需要先完成其他依赖命令
3. 如果命令执行失败，可以尝试先执行数据库配置命令
4. 执行这些命令时，请确保在项目根目录下运行
5. 部分命令可能需要较长时间完成，取决于数据量大小
6. 声音文件处理可能需要额外的时间和存储空间，确保有足够的资源

---

> **文档最后更新**: 2025-12-23