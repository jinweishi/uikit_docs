| 错误码 | 描述 | 处理建议 |
| ----- | ---- | ------- |
| 0 | 执行成功。| - |
| 5000001 | License 格式无效。 | 请确认 License 是否正确。|
| 5000002 | License 已过期。 | 请重新生成 License。|
| 5000004 | License 不包含当前平台的授权。 | 请联系 ZEGO 技术支持确认。 |
| 5000005 | 当前应用不支持该 License。 | 请联系 ZEGO 技术支持确认。 |
| 5000006 | 初始化 AvatarService 时，没有进行鉴权。 | 请在初始化 AvatarService 时，传入 License，鉴权通过后才能进行其他操作。 |
| 5000007 | 请求 License 异常。 | 请联系 ZEGO 技术支持处理。 |
| 5000101 | 参数有误。 | 请检查您的输入参数 AppID 是否正确，或 AppSign 是否为空。 |
| 5000102 | Token（AppSign）有误。 | AppSign 不正确，请联系 ZEGO 技术支持处理。 |
| 5000103 | 证书无效。 | AppId 或者包名不正确、或不匹配。请联系 ZEGO 技术支持确认代码和配置是否正确。 |
| 5000104 | 服务内部问题。 | 请联系 ZEGO 技术支持处理。 |
| 5000105 | 其他网络错误。 | 请检查网络。 |
| 5000200 | 证书不支持此功能。 | 请联系 ZEGO 技术支持处理。 |
| 5000201 | License 不包含 AI 捏脸功能的授权。 | 请联系 ZEGO 技术支持确认。 |
| 5000202 | License 不包含手动捏脸、妆容换妆等功能的授权。 | 请联系 ZEGO 技术支持确认。 |
| 5000203 | License 不包含表情随动功能的授权。| 请联系 ZEGO 技术支持确认。 |
| 5000204 | 缺少可用的 License。 | 请确认鉴权是否成功。 |
| 5000205 | 指定路径的文件不存在。 | 请确认路径填写是否正确。 |
| 5000206 | 证书不支持语音驱动特性。 | 请联系 ZEGO 技术支持处理。 |
| 5000207 | License 证书不支持肢体驱动特性。 | 请联系 ZEGO 技术支持处理。 |
| 5000209 | License证书不支持场景和特效。 | 请联系 ZEGO 技术支持处理。 |
| 5000301 | 初始化失败，内存不足。 | 请更换设备重试。 |
| 6000001 | 录制输出文件创建错误。 | 请参考 `startRecord` 回调错误信息处理。 |
| 6000002 | 录制出错过程中出现错误，可能是某一帧数据没有录制成功。| 请重试，或联系 ZEGO 技术支持处理。|
| 6000003 | 当前文件正在录制。 | 请结束当前录制。 |
| 6000004 | 录制宽度设置错误。 | 录制宽度请不要大于 avatarView 的宽度。 |
| 6000005 | 手机硬件不支持录制。 | 请更换设备。 |
| 6000006 | 录制时硬件配置出错。 | 请更换设备重试。 |
| 6000007 | 录制时音频硬件配置出错。 | 请更换设备重试。 |
| 6000100 | 摄像头打开失败。 | 请重试，或联系 ZEGO 技术支持处理。 |
| 6000101 | 没有权限打开摄像头。 | 请授权。 |
| 6000102 | 没有权限打开麦克风。 | 请授权。 |
| 6000200 | 传入路径为空。 | 请确认路径是否正确。 |
| 6000201 | 路径不存在。 | 请确认路径是否正确。 |
| 6000300 | 创建模型失败。 | 请重试，或联系 ZEGO 技术支持处理。 |
| 6000301 | 模型资源路径错误。 | 请确认路径是否正确。 |
| 6000400 | 上下文为空。 | 请重试，或联系 ZEGO 技术支持处理。 |
| 6000401 | 使用被销毁的view。 | 请联系 ZEGO 技术支持确认代码和配置是否正确。 |
| 6000500 | Avatar 推流缺少 Character。 | 请联系 ZEGO 技术支持确认代码和配置是否正确。 |
| 6000501 | 不可推流。 | 请联系 ZEGO 技术支持处理。 |
| 7000001 | 使用 AR 驱动时，metal 系统兼容性错误。 | 请联系 ZEGO 技术支持处理。 |
| 7000002 | 使用 AR 驱动时，SDK 没有收到摄像头数据。 | 请检查摄像头设置或者输入摄像头数据。 |
| 7000003 | License 不包含 AR 驱动功能的授权。 | 请联系 ZEGO 技术支持确认。 |
| 7000004 | 未创建 Avatar 对象。 | 请确认人模是否创建成功，或联系 ZEGO 技术支持处理。 |
| 1000001 | 未知错误。 | 请联系 ZEGO 技术支持处理。 |































