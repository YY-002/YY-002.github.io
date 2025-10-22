<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>方贵干飞行学院 - 专业驾驶培训</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#165DFF',
                        secondary: '#FF7D00',
                        dark: '#1D2939'
                    }
                }
            }
        }
    </script>
    
    <style type="text/tailwindcss">
        @layer utilities {
            .content-auto {
                content-visibility: auto;
            }
            .text-shadow {
                text-shadow: 0 2px 4px rgba(0,0,0,0.3);
            }
        }
    </style>
</head>
<body class="font-sans text-gray-800">
    <!-- 导航栏 -->
    <header class="bg-white shadow-md fixed w-full top-0 z-50">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i class="fa fa-plane text-primary text-2xl"></i>
                <span class="font-bold text-xl text-dark">方贵干飞机培训学院</span>
            </div>
            
            <nav class="hidden md:flex space-x-6">
                <a href="#home" class="hover:text-primary transition-colors">首页</a>
                <a href="#courses" class="hover:text-primary transition-colors">课程</a>
                <a href="#features" class="hover:text-primary transition-colors">优势</a>
                <a href="#instructors" class="hover:text-primary transition-colors">教练</a>
                <a href="#contact" class="hover:text-primary transition-colors">联系我们</a>
            </nav>
            
            <button class="md:hidden text-dark text-xl">
                <i class="fa fa-bars"></i>
            </button>
        </div>
    </header>

    <!-- 英雄区域 -->
    <section id="home" class="pt-24 md:pt-0 min-h-screen flex items-center relative">
        <div class="absolute inset-0 z-0">
            <img src="C:\Users\lzd\Desktop\微信图片_20251022210939.jpg" alt="飞机飞行在天空中" class="w-full h-full object-cover">
            <div class="absolute inset-0 bg-dark/50"></div>
        </div>
        
        <div class="container mx-auto px-4 z-10 py-16">
            <div class="max-w-2xl text-white">
                <h1 class="text-[clamp(2rem,5vw,3.5rem)] font-bold mb-6 text-shadow leading-tight">
                    实现你的飞行梦想
                </h1>
                <p class="text-lg md:text-xl mb-8 opacity-90">
                    专业的飞行培训课程，从理论到实践，助你成为合格飞行员
                </p>
                <div class="flex flex-wrap gap-4">
                    <a href="#courses" class="bg-secondary hover:bg-secondary/90 text-white px-6 py-3 rounded-lg font-medium transition-all">
                        查看课程
                    </a>
                    <a href="#contact" class="bg-white/10 hover:bg-white/20 backdrop-blur-sm text-white border border-white px-6 py-3 rounded-lg font-medium transition-all">
                        立即咨询
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- 课程介绍 -->
    <section id="courses" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-[clamp(1.5rem,3vw,2.5rem)] font-bold text-dark mb-3">飞行培训课程</h2>
                <div class="w-20 h-1 bg-primary mx-auto mb-4"></div>
                <p class="text-gray-600 max-w-2xl mx-auto">根据不同需求和经验水平，我们提供多种飞行培训课程</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- 私人飞行员执照课程 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-lg transition-shadow">
                    <div class="h-48 overflow-hidden">
                        <img src="https://tse2-mm.cn.bing.net/th/id/OIP-C.9Vv24Nc7rW4epJYaB2XscwHaE7?w=262&h=180&c=7&r=0&o=7&pid=1.7&rm=3" alt="私人飞行员执照课程" class="w-full h-full object-cover hover:scale-105 transition-transform duration-500">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2 text-dark">私人飞行员执照</h3>
                        <p class="text-gray-600 mb-4">适合初学者，掌握基本飞行技能，获得私人飞行资格</p>
                        <div class="flex justify-between items-center">
                            <span class="text-primary font-bold">38,000元起</span>
                            <a href="#contact" class="text-secondary hover:underline">了解详情 <i class="fa fa-arrow-right ml-1"></i></a>
                        </div>
                    </div>
                </div>
                
                <!-- 商业飞行员执照课程 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-lg transition-shadow">
                    <div class="h-48 overflow-hidden">
                        <img src="https://tse4-mm.cn.bing.net/th/id/OIP-C.raLSReRZgRj2xfRMxZpWTQHaE8?w=255&h=180&c=7&r=0&o=7&pid=1.7&rm=3" alt="商业飞行员执照课程" class="w-full h-full object-cover hover:scale-88 transition-transform duration-288">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2 text-dark">商业飞行员执照</h3>
                        <p class="text-gray-600 mb-4">专业级培训，满足商业飞行标准，可从事职业飞行</p>
                        <div class="flex justify-between items-center">
                            <span class="text-primary font-bold">86,000元起</span>
                            <a href="#contact" class="text-secondary hover:underline">了解详情 <i class="fa fa-arrow-right ml-1"></i></a>
                        </div>
                    </div>
                </div>
                
                <!-- 飞行体验课程 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-lg transition-shadow">
                    <div class="h-48 overflow-hidden">
                        <img src="https://tse4-mm.cn.bing.net/th/id/OIP-C.NZe3pRL1UcGyae1U8bT1ZgHaE8?w=278&h=186&c=7&r=0&o=5&pid=1.7" alt="飞行体验课程" class="w-full h-full object-cover hover:scale-105 transition-transform duration-500">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2 text-dark">飞行体验课程</h3>
                        <p class="text-gray-600 mb-4">短时间体验飞行乐趣，由教练陪同，适合飞行爱好者</p>
                        <div class="flex justify-between items-center">
                            <span class="text-primary font-bold">1,600元起</span>
                            <a href="#contact" class="text-secondary hover:underline">了解详情 <i class="fa fa-arrow-right ml-1"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 我们的优势 -->
    <section id="features" class="py-16">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-[clamp(1.5rem,3vw,2.5rem)] font-bold text-dark mb-3">为什么选择我们</h2>
                <div class="w-20 h-1 bg-primary mx-auto mb-4"></div>
                <p class="text-gray-600 max-w-2xl mx-auto">专业的教学团队和完善的教学设施，为您提供优质的飞行培训体验</p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="text-center p-6 hover:bg-gray-50 rounded-lg transition-colors">
                    <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fa fa-graduation-cap text-primary text-2xl"></i>
                    </div>
                    <h3 class="font-bold text-lg mb-2">专业教练</h3>
                    <p class="text-gray-600">平均拥有10年以上飞行经验的专业教练团队</p>
                </div>
                
                <div class="text-center p-6 hover:bg-gray-50 rounded-lg transition-colors">
                    <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fa fa-plane text-primary text-2xl"></i>
                    </div>
                    <h3 class="font-bold text-lg mb-2">先进设备</h3>
                    <p class="text-gray-600">现代化训练飞机和飞行模拟器，确保训练质量</p>
                </div>
                
                <div class="text-center p-6 hover:bg-gray-50 rounded-lg transition-colors">
                    <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fa fa-certificate text-primary text-2xl"></i>
                    </div>
                    <h3 class="font-bold text-lg mb-2">权威认证</h3>
                    <p class="text-gray-600">民航局认可的飞行培训资质，证书全球通用</p>
                </div>
                
                <div class="text-center p-6 hover:bg-gray-50 rounded-lg transition-colors">
                    <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fa fa-clock-o text-primary text-2xl"></i>
                    </div>
                    <h3 class="font-bold text-lg mb-2">灵活安排</h3>
                    <p class="text-gray-600">根据学员时间灵活安排训练，高效完成课程</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 教练团队 -->
    <section id="instructors" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-[clamp(1.5rem,3vw,2.5rem)] font-bold text-dark mb-3">专业教练团队</h2>
                <div class="w-20 h-1 bg-primary mx-auto mb-4"></div>
                <p class="text-gray-600 max-w-2xl mx-auto">我们的教练拥有丰富的飞行经验和教学经验，确保您获得最佳培训效果</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white rounded-xl shadow-sm overflow-hidden hover:shadow-md transition-shadow">
                    <img src="https://tse4-mm.cn.bing.net/th/id/OIP-C.BdJTEBkXxuPwEOVTYYhwFwHaLJ?w=186&h=281&c=7&r=0&o=5&pid=1.7" alt="方教练" class="w-full h-72 object-cover">
                    <div class="p-6 text-center">
                        <h3 class="font-bold text-xl mb-1">方贵干</h3>
                        <p class="text-primary mb-3">总飞行教官</p>
                        <p class="text-gray-600 mb-4">88年飞行经验，安全飞行15,000小时</p>
                        <div class="flex justify-center space-x-3">
                            <a href="#" class="text-gray-500 hover:text-primary"><i class="fa fa-weixin"></i></a>
                            <a href="#" class="text-gray-500 hover:text-primary"><i class="fa fa-phone"></i></a>
                        </div>
                    </div>
                </div>
                
                <div class="bg-white rounded-xl shadow-sm overflow-hidden hover:shadow-md transition-shadow">
                    <img src="https://tse1-mm.cn.bing.net/th/id/OIP-C.Blh_ZZZhXr0wF7wDIwpoKwHaLJ?w=186&h=281&c=7&r=0&o=5&pid=1.7" alt="杨教练" class="w-full h-72 object-cover">
                    <div class="p-6 text-center">
                        <h3 class="font-bold text-xl mb-1">杨家肥</h3>
                        <p class="text-primary mb-3">高级飞行教官</p>
                        <p class="text-gray-600 mb-4">58年飞行经验，前徐闻县前山航空公司机长</p>
                        <div class="flex justify-center space-x-3">
                            <a href="#" class="text-gray-500 hover:text-primary"><i class="fa fa-weixin"></i></a>
                            <a href="#" class="text-gray-500 hover:text-primary"><i class="fa fa-phone"></i></a>
                        </div>
                    </div>
                </div>
                
                <div class="bg-white rounded-xl shadow-sm overflow-hidden hover:shadow-md transition-shadow">
                    <img src="https://tse4-mm.cn.bing.net/th/id/OIP-C.Xf1OkCkChX0l3S-qrb38tQHaLJ?w=186&h=280&c=7&r=0&o=5&pid=1.7" alt="梁教练" class="w-full h-72 object-cover">
                    <div class="p-6 text-center">
                        <h3 class="font-bold text-xl mb-1">梁志铭</h3>
                        <p class="text-primary mb-3">飞行理论教官</p>
                        <p class="text-gray-600 mb-4">航空理论专家，10年教学经验</p>
                        <div class="flex justify-center space-x-3">
                            <a href="#" class="text-gray-500 hover:text-primary"><i class="fa fa-weixin"></i></a>
                            <a href="#" class="text-gray-500 hover:text-primary"><i class="fa fa-phone"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 联系我们 -->
    <section id="contact" class="py-16">
        <div class="container mx-auto px-4">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-[clamp(1.5rem,3vw,2.5rem)] font-bold text-dark mb-4">联系我们</h2>
                    <div class="w-20 h-1 bg-primary mb-6"></div>
                    <p class="text-gray-600 mb-8">如有任何疑问或需要了解更多信息，请随时联系我们，我们将尽快回复您</p>
                    
                    <div class="space-y-4 mb-8">
                        <div class="flex items-start">
                            <div class="mt-1 mr-4 text-primary">
                                <i class="fa fa-map-marker"></i>
                            </div>
                            <div>
                                <h3 class="font-bold mb-1">地址</h3>
                                <p class="text-gray-600">湛江徐闻国际机场航空培训中心</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="mt-1 mr-4 text-primary">
                                <i class="fa fa-phone"></i>
                            </div>
                            <div>
                                <h3 class="font-bold mb-1">电话</h3>
                                <p class="text-gray-600">400-888-9999</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="mt-1 mr-4 text-primary">
                                <i class="fa fa-envelope"></i>
                            </div>
                            <div>
                                <h3 class="font-bold mb-1">邮箱</h3>
                                <p class="text-gray-600">info@feixingxueyuan.com</p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="flex space-x-4">
                        <a href="#" class="w-10 h-10 bg-primary/10 hover:bg-primary/20 rounded-full flex items-center justify-center text-primary transition-colors">
                            <i class="fa fa-weixin"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-primary/10 hover:bg-primary/20 rounded-full flex items-center justify-center text-primary transition-colors">
                            <i class="fa fa-weibo"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-primary/10 hover:bg-primary/20 rounded-full flex items-center justify-center text-primary transition-colors">
                            <i class="fa fa-youtube-play"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <form class="bg-white p-8 rounded-xl shadow-md">
                        <h3 class="text-xl font-bold mb-6 text-dark">预约咨询</h3>
                        
                        <div class="mb-4">
                            <label for="name" class="block text-gray-700 mb-2">姓名</label>
                            <input type="text" id="name" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="请输入您的姓名">
                        </div>
                        
                        <div class="mb-4">
                            <label for="phone" class="block text-gray-700 mb-2">电话</label>
                            <input type="tel" id="phone" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="请输入您的电话">
                        </div>
                        
                        <div class="mb-4">
                            <label for="course" class="block text-gray-700 mb-2">感兴趣的课程</label>
                            <select id="course" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent">
                                <option value="">请选择课程</option>
                                <option value="private">私人飞行员执照</option>
                                <option value="commercial">商业飞行员执照</option>
                                <option value="experience">飞行体验课程</option>
                                <option value="other">其他课程</option>
                            </select>
                        </div>
                        
                        <div class="mb-6">
                            <label for="message" class="block text-gray-700 mb-2">留言</label>
                            <textarea id="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="请输入您的疑问或需求"></textarea>
                        </div>
                        
                        <button type="submit" class="w-full bg-primary hover:bg-primary/90 text-white font-medium py-3 px-4 rounded-lg transition-colors">
                            提交预约
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- 页脚 -->
    <footer class="bg-dark text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid md:grid-cols-4 gap-8 mb-8">
                <div>
                    <div class="flex items-center space-x-2 mb-4">
                        <i class="fa fa-plane text-primary text-2xl"></i>
                        <span class="font-bold text-xl">方贵干飞机培训学院</span>
                    </div>
                    <p class="text-gray-400 mb-4">专业的飞行培训，助您实现飞行梦想</p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-white transition-colors">
                            <i class="fa fa-weixin"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white transition-colors">
                            <i class="fa fa-weibo"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white transition-colors">
                            <i class="fa fa-youtube-play"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h3 class="font-bold text-lg mb-4">快速链接</h3>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-white transition-colors">首页</a></li>
                        <li><a href="#courses" class="text-gray-400 hover:text-white transition-colors">课程</a></li>
                        <li><a href="#features" class="text-gray-400 hover:text-white transition-colors">优势</a></li>
                        <li><a href="#instructors" class="text-gray-400 hover:text-white transition-colors">教练</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white transition-colors">联系我们</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="font-bold text-lg mb-4">课程</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">私人飞行员执照</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">商业飞行员执照</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">飞行体验课程</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">飞行员复训</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">航空理论课程</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="font-bold text-lg mb-4">联系方式</h3>
                    <ul class="space-y-2">
                        <li class="flex items-center text-gray-400">
                            <i class="fa fa-map-marker mr-2"></i>
                            <span>湛江徐闻国际机场</span>
                        </li>
                        <li class="flex items-center text-gray-400">
                            <i class="fa fa-phone mr-2"></i>
                            <span>400-888-9999</span>
                        </li>
                        <li class="flex items-center text-gray-400">
                            <i class="fa fa-envelope mr-2"></i>
                            <span>info@feixingxueyuan.com</span>
                        </li>
                        <li class="flex items-center text-gray-400">
                            <i class="fa fa-clock-o mr-2"></i>
                            <span>周一至周日 9:00-18:00</span>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-800 pt-8 text-center text-gray-500">
                <p>&copy; 2023 方贵干飞机培训学院 版权所有 | 京ICP备12345678号</p>
            </div>
        </div>
    </footer>

    <script>
        // 简单的滚动效果
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');# YY-002.github.io
