# 5_216
Java多线程与并发库高级应用视频教程
<br/></br>
<h3>微:mukewang8 资源编号：52216</h3>
<br/></br>
<div id="page" class="hfeed site">
<div id="content" class="site-content shadow">
<div id="primary" class="content-area">
<article id="post-1320" class="post-1320 post type-post status-publish format-standard hentry category-java tag-185 iel">
<div class="entry-content">
<div class="single-content">
<h3>知识点：</h3>
<p>Java线程具有五中基本状态</p>
<p><strong><span style="color: red;">新建状态（New）：</span></strong></p>
<blockquote><p>当线程对象对创建后，即进入了新建状态，如：Thread t = new MyThread();</p></blockquote>
<p><strong><span style="color: red;">就绪状态（Runnable）：</span></strong></p>
<blockquote><p>当调用线程对象的start()方法（t.start();），线程即进入就绪状态。处于就绪状态的线程，只是说明此线程已经做好了准备，随时等待CPU调度执行，并不是说执行了t.start()此线程立即就会执行；</p></blockquote>
<p><strong><span style="color: red;">运行状态（Running）：</span></strong></p>
<blockquote><p>当CPU开始调度处于就绪状态的线程时，此时线程才得以真正执行，即进入到运行状态。注：就&nbsp;&nbsp;&nbsp;&nbsp; 绪状态是进入到运行状态的唯一入口，也就是说，线程要想进入运行状态执行，首先必须处于就绪状态中；</p></blockquote>
<p><strong><span style="color: red;">阻塞状态（Blocked）：</span></strong></p>
<blockquote><p>处于运行状态中的线程由于某种原因，暂时放弃对CPU的使用权，停止执行，此时进入阻塞状态，直到其进入到就绪状态，才 有机会再次被CPU调用以进入到运行状态。根据阻塞产生的原因不同，阻塞状态又可以分为三种：</p>
<p>1.等待阻塞：运行状态中的线程执行wait()方法，使本线程进入到等待阻塞状态；</p>
<p>2.同步阻塞 -- 线程在获取synchronized同步锁失败(因为锁被其它线程所占用)，它会进入同步阻塞状态；</p>
<p>3.其他阻塞 -- 通过调用线程的sleep()或join()或发出了I/O请求时，线程会进入到阻塞状态。当sleep()状态超时、join()等待线程终止或者超时、或者I/O处理完毕时，线程重新转入就绪状态。</p></blockquote>
<p><strong><span style="color: red;">死亡状态（Dead）：</span></strong></p>
<blockquote><p>线程执行完了或者因异常退出了run()方法，该线程结束生命周期。</p></blockquote>
</div>
</div>
</article>
</div>
</div>
</div>
<h3>课程目录：</h3>
<blockquote><p>源代码与资料</p>
<p>1_传统线程技术回顾.avi</p>
<p>2_传统定时器技术回顾.avi</p>
<p>3_传统线程互斥技术.avi</p>
<p>4_传统线程同步通信技术.avi</p>
<p>5_线程范围内共享变量的概念与作用.avi</p>
<p>6_ThreadLocal类及应用技巧.avi</p>
<p>7_多个线程之间共享数据的方式探讨.avi</p>
<p>8_java5原子性操作类的应用.avi</p>
<p>9_java5线程并发库的应用.avi</p>
<p>10_Callable与Future的应用.avi</p>
<p>11_java5的线程锁技术.avi</p>
<p>12_java5读写锁技术的妙用.avi</p>
<p>13_java5条件阻塞Condition的应用.avi</p>
<p>14_java5的Semaphere同步工具.avi</p>
<p>15_java5的CyclicBarrier同步工具.avi</p>
<p>16_java5的CountDownLatch同步工具.avi</p>
<p>17_java5的Exchanger同步工具.avi</p>
<p>18_java5阻塞队列的应用.avi</p>
<p>19_java5同步集合类的应用.avi</p>
<p>20_空中网挑选实习生的面试题1.avi</p>
<p>21_空中网挑选实习生的面试题2.avi</p>
<p>22_空中网挑选实习生的面试题3.avi</p></blockquote>
<p><img src="https://www.ko996.com/wp-content/uploads/img/2017/10/1-21-300x180.png" alt="Java多线程与并发库高级应用视频教程"></p>


	<div class="reply-read">
		<div class="reply-ts">
			<div class="read-sm"><i class="fa fa-exclamation-circle"></i>此处为隐藏的内容！</div>
			<div class="read-sm"><i class="fa fa-spinner"></i>发表评论并刷新，才能查看</div>
		</div>
		<div class="read-pl"><a>发表评论</a></div>
		
    </div>
