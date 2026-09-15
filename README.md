## 目前，在GitHub上的这个testgit仓库还是空的，GitHub告诉我们，可以从这个仓库克隆出新的仓库，也可以把一个已有的本地仓库与之关联，然后，把本地仓库的内容推送到GitHub仓库。 528P3

更新时间：2026-09-15 07:00:54.189

3z05uv.hoodamath2.com
2l0p3f.compasslandconsultants.com
45z84g.hoodamath2.com
30x386.kvb1987.com
那么一般情况下，那些分支要推送呢？
3suisu.kvb1988.com
2w9i2y.kvb1988.com
3saze7.kvb1987.com
3ax8t3.misturabela.com
2vpdmp.hoodamath2.com
32infz.kvb1993.com
可以看到 推送成功了，如果我们现在要推送到其他分支，比如dev分支上，我们还是那个命令 git push origin dev
3qpudn.kvb1996.com
Git算不算程序员的必备技能？
47f7wi.hoodamath2.com
3b3wxe.misturabela.com
2qziot.kvb1979.com
我们可以看到如上，推送成功，我们可以继续来截图github上的readme.txt内容 如下：
3ao5px.hoodamath2.com
Git算不算程序员的必备技能？
3l9gua.kvb1996.com
30v7ni.ecvyksp.cn
3o0gb1.kvb1997.com
现在我想把本地更新的readme.txt代码推送到远程库中，使用命令如下：
3coyry.kvb1993.com
4htfzd.kvb1998.com
3svyay.kvb1988.com
3e5ccb.cdroutlet.com
3kbvn4.kvb1985.com
3chdee.kvb1982.com
3vkkwe.kvb1996.com
2rw4sr.hoodamath2.com
3y8hu2.hoodamath2.com
Git算不算程序员的必备技能？
442c6o.ecvyksp.cn
3jdqxq.kvb1992.com
4idm15.kvb1992.com
3zm4jk.hothairybushes.com
369v3s.kvb1979.com
33qtiz.kvb1980.com
2w0vyb.kvb1981.com
本地的readme.txt代码如下：
4bocs4.kvb1987.com
3hxr8r.kvb1999.com
Git算不算程序员的必备技能？
3ui2rd.kvb1998.com
比如我现在的github上的readme.txt代码如下：
4j3w59.kvb1989.com
409ram.hongyihualang.cn
3shy77.kvb1985.com
32a8kx.kvb1988.com
使用命令 git push origin master
3l9tqt.kvb1980.com
3u4qwy.kvb1987.com
推送分支就是把该分支上所有本地提交到远程库中，推送时，要指定本地分支，这样，Git就会把该分支推送到远程库对应的远程分支上：
41m3qt.misturabela.com
2t933t.kvb1999.com
3sk73q.hoodamath2.com
一：推送分支：
30ymzk.kvb1989.com
Git算不算程序员的必备技能？
3omjgr.kvb1997.com
40vwpo.kvb1979.com
32qr5k.compasslandconsultants.com
3eudph.kvb1992.com
3mb9ke.kvb1991.com
如下演示：
43tz6c.kvb1993.com
348ttl.cdroutlet.com
3qkzj1.misturabela.com
要查看远程库的详细信息 使用 git remote –v
432dsw.kvb1983.com
42zf1e.cdroutlet.com
要查看远程库的信息 使用 git remote
3pgv4k.compasslandconsultants.com
2s81ab.compasslandconsultants.com
2np0aw.compasslandconsultants.com
当你从远程库克隆时候，实际上Git自动把本地的master分支和远程的master分支对应起来了，并且远程库的默认名称是origin。
34qcdx.hoodamath2.com
44uikz.misturabela.com
八：多人协作。
3ni6iv.kvb1982.com
38wyk0.kvb1999.com
Git算不算程序员的必备技能？
37bepq.kvb1978.com
34fceg.hongyihualang.cn
演示如下
3iw24k.kvb1987.com
2.另一种方式是使用git stash pop,恢复的同时把stash内容也删除了。
3msqn6.kvb1993.com
1.git stash apply恢复，恢复后，stash内容并不删除，你需要使用命令git stash drop来删除。
394ome.kvb1998.com
工作现场还在，Git把stash内容存在某个地方了，但是需要恢复一下，可以使用如下2个方法：
2z2xp2.hongyihualang.cn
2o6ezw.hothairybushes.com
3ahpyg.kvb1985.com
3wve20.kvb1993.com
Git算不算程序员的必备技能？
40027d.kvb1999.com
3xjofa.kvb1980.com
2sq9jd.kvb1978.com
工作区是干净的，那么我们工作现场去哪里呢？我们可以使用命令 git stash list来查看下。如下：
3svuy0.cdroutlet.com
Git算不算程序员的必备技能？
414acd.hothairybushes.com
31ai2u.kvb1985.com
3f5o0b.compasslandconsultants.com
3h4n2n.kvb1991.com
40bd1z.hothairybushes.com
2wxw8t.kvb1991.com
4j2ayo.kvb1998.com
现在，我们回到dev分支上干活了。
454bac.kvb1982.com
Git算不算程序员的必备技能？
3lhn3m.ecvyksp.cn
3tag4s.kvb1995.com
3b5pq3.kvb1991.com
修复完成后，切换到master分支上，并完成合并，最后删除issue-404分支。演示如下：
3v3fcm.kvb1991.com
Git算不算程序员的必备技能？
3nbb20.kvb1989.com
2zjh7r.kvb1989.com
首先我们要确定在那个分支上修复bug，比如我现在是在主分支master上来修复的，现在我要在master分支上创建一个临时分支，演示如下：
48dtxy.cdroutlet.com
3jb26u.misturabela.com
所以现在我可以通过创建issue-404分支来修复bug了。
362039.kvb1983.com
34tkz9.kvb1997.com
463fny.hoodamath2.com
Git算不算程序员的必备技能？
3a82jj.kvb1996.com
39y3q2.hothairybushes.com
并不是我不想提交，而是工作进行到一半时候，我们还无法提交，比如我这个分支bug要2天完成，但是我issue-404 bug需要5个小时内完成。怎么办呢？还好，Git还提供了一个stash功能，可以把当前工作现场 ”隐藏起来”，等以后恢复现场后继续工作。如下：
381nty.kvb1980.com
484w8o.kvb1996.com
42cl39.kvb1978.com
Git算不算程序员的必备技能？
3kingu.kvb1990.com
3e2hfj.inmolopez.com
3pqnr7.misturabela.com
3cn2jd.kvb1988.com
2wsm3e.kvb1990.com
2mx2o9.hothairybushes.com
比如我在开发中接到一个404 bug时候，我们可以创建一个404分支来修复它，但是，当前的dev分支上的工作还没有提交。比如如下：
32hcmp.ecvyksp.cn
2wk0br.hongyihualang.cn
389c6e.hothairybushes.com
2x0nfc.hothairybushes.com
39f0hx.misturabela.com
47etb1.hothairybushes.com
3boqq6.kvb1980.com
在开发中，会经常碰到bug问题，那么有了bug就需要修复，在Git中，分支是很强大的，每个bug都可以通过一个临时分支来修复，修复完成后，合并分支，然后将临时的分支删除掉。
49jgst.hongyihualang.cn
3y7098.compasslandconsultants.com
2l5yez.hothairybushes.com
七：bug分支：
3p4uvg.cdroutlet.com
分支策略：首先master主分支应该是非常稳定的，也就是用来发布新版本，一般情况下不允许在上面干活，干活一般情况下在新建的dev分支上干活，干完后，比如上要发布，或者说dev分支代码稳定后可以合并到主分支master上来。
35ztxn.misturabela.com
4g71iy.kvb1987.com
4ehbku.kvb1991.com
2mjexq.hongyihualang.cn
2z05z6.ecvyksp.cn
33strs.hothairybushes.com
Git算不算程序员的必备技能？
3mm7k9.kvb1998.com
44na8r.kvb1986.com
3f2swu.kvb1997.com
3ywm45.hoodamath2.com
44pyrz.compasslandconsultants.com
4729y0.ecvyksp.cn
创建一个dev分支。 修改readme.txt内容。 添加到暂存区。 切换回主分支(master)。 合并dev分支，使用命令 git merge –no-ff -m “注释” dev 查看历史记录 截图如下：
4hb2j0.kvb1988.com
通常合并分支时，git一般使用”Fast forward”模式，在这种模式下，删除分支后，会丢掉分支信息，现在我们来使用带参数 –no-ff来禁用”Fast forward”模式。首先我们来做demo演示下：
38t38c.compasslandconsultants.com
3.分支管理策略。
3kq4bq.kvb1982.com
31rceh.inmolopez.com
379usv.kvb1998.com
Git算不算程序员的必备技能？
35anvc.kvb1986.com
3cmrt1.kvb1992.com
3jjrxk.kvb1991.com
4hjmdo.kvb1996.com
3hwddt.misturabela.com
2lul35.hongyihualang.cn
2xceaw.compasslandconsultants.com
3cwyla.kvb1980.com
44jpjv.ecvyksp.cn
324si4.compasslandconsultants.com
446fen.kvb1989.com
3rbf5m.kvb1985.com
如果我想查看分支合并的情况的话，需要使用命令 git log.命令行演示如下：
49jx47.hoodamath2.com
2yv6ci.kvb1999.com
3uf41w.kvb1989.com
38tkya.ecvyksp.cn
Git算不算程序员的必备技能？
3y70hh.kvb1987.com
33k3vm.misturabela.com
34afj5.ecvyksp.cn
4hk5c6.kvb1986.com
45vceo.kvb1989.com
43t9bm.kvb1982.com
2w1tpc.misturabela.com
Git用，=======，标记出不同分支的内容，其中HEAD是指主分支修改的内容，fenzhi1 是指fenzhi1上修改的内容，我们可以修改下如下后保存：
3z4veo.kvb1978.com
48tbpl.kvb1989.com
4fk75t.kvb1987.com
Git算不算程序员的必备技能？
4e4z9a.kvb1981.com
现在我们需要在master分支上来合并fenzhi1，如下操作：
3en0xf.hongyihualang.cn
Git算不算程序员的必备技能？
361mgw.cdroutlet.com
3a8aqv.kvb1980.com
3i3gnu.kvb1982.com
3lw7xc.ecvyksp.cn
3s2nso.kvb1999.com
同样，我们现在切换到master分支上来，也在最后一行添加内容，内容为99999999，如下所示：
35svae.kvb1978.com
2kx16y.cdroutlet.com
Git算不算程序员的必备技能？
42oyun.compasslandconsultants.com
2ys17s.kvb1991.com
4aznu5.kvb1989.com
下面我们还是一步一步来，先新建一个新分支，比如名字叫fenzhi1，在readme.txt添加一行内容8888888，然后提交，如下所示：
48hkb4.kvb1990.com
360ocl.kvb1996.com
如何解决冲突？
2t0q3b.inmolopez.com
3og5m6.kvb1995.com
3nld64.cdroutlet.com
38goqh.kvb1983.com
3aljee.cdroutlet.com
3mwybs.kvb1995.com
3ffytn.hothairybushes.com
删除分支：git branch –d name
3tkmm6.kvb1985.com
32ll4l.compasslandconsultants.com
合并某分支到当前分支：git merge name
4c3lde.kvb1999.com
创建+切换分支：git checkout –b name
3jxo7c.kvb1980.com
切换分支：git checkout name
3thl5a.misturabela.com
创建分支：git branch name
36rrcb.kvb1991.com
4icsqj.kvb1999.com
41oazb.compasslandconsultants.com
3pt41b.kvb1993.com
38xzru.compasslandconsultants.com
查看分支：git branch
359chx.hoodamath2.com
总结创建与合并分支命令如下：
2qjdql.ecvyksp.cn
33zmfv.inmolopez.com
Git算不算程序员的必备技能？
2ov1wl.hoodamath2.com
合并完成后，我们可以接着删除dev分支了，操作如下：
479uar.kvb1979.com
34ybuh.ecvyksp.cn
注意到上面的Fast-forward信息，Git告诉我们，这次合并是“快进模式”，也就是直接把master指向dev的当前提交，所以合并速度非常快。
3gjedt.kvb1990.com
46bkh9.kvb1986.com
git merge命令用于合并指定分支到当前分支上，合并后，再查看readme.txt内容，可以看到，和dev分支最新提交的是完全一样的。
3z2whz.hongyihualang.cn
3kzlm1.kvb1985.com
Git算不算程序员的必备技能？
2wb4j8.hoodamath2.com
现在我们可以把dev分支上的内容合并到分支master上了，可以在master分支上，使用如下命令 git merge dev 如下所示：
3ruo97.inmolopez.com
2s4s12.kvb1996.com
43y6hj.hothairybushes.com
38ghxd.ecvyksp.cn
Git算不算程序员的必备技能？
2sh318.ecvyksp.cn
3lcwsh.misturabela.com
387umq.kvb1987.com
437r7p.cdroutlet.com
3dchsv.hothairybushes.com
2xbrkj.kvb1982.com
3d9q3x.kvb1998.com
现在dev分支工作已完成，现在我们切换到主分支master上，继续查看readme.txt内容如下：
3ny8yc.inmolopez.com
3t4cfk.ecvyksp.cn
41jftf.hongyihualang.cn
4bpjpb.kvb1986.com
Git算不算程序员的必备技能？
3yxapl.compasslandconsultants.com
3tiu4b.misturabela.com
3904bz.kvb1988.com
首先我们先来查看下readme.txt内容，接着添加内容77777777，如下：
3qopj1.hoodamath2.com
38joxf.inmolopez.com
3a993k.kvb1990.com
372ibm.misturabela.com
git branch查看分支，会列出所有的分支，当前分支前面会添加一个星号。然后我们在dev分支上继续做demo，比如我们现在在readme.txt再增加一行 7777777777777
4ha0qx.kvb1999.com
git checkout dev
3rgl3i.ecvyksp.cn
3qp8ee.hothairybushes.com
2uwf6v.cdroutlet.com
3ttjtn.compasslandconsultants.com
git branch dev
3xl3h2.hothairybushes.com
47vjfa.misturabela.com
git checkout 命令加上 –b参数表示创建并切换，相当于如下2条命令
3ndgla.misturabela.com
Git算不算程序员的必备技能？
2vtz04.compasslandconsultants.com
首先，我们来创建dev分支，然后切换到dev分支上。如下操作：
3zu3nm.kvb1981.com
在 版本回填退里，你已经知道，每次提交，Git都把它们串成一条时间线，这条时间线就是一个分支。截止到目前，只有一条时间线，在Git里，这个分支叫主分支，即master分支。HEAD严格来说不是指向提交，而是指向master，master才是指向提交的，所以，HEAD指向的就是当前分支。
3o5k4l.hothairybushes.com
六：创建与合并分支。
3omzcu.kvb1998.com
Git算不算程序员的必备技能？
41y784.kvb1995.com
3y5k5d.ecvyksp.cn
3liis1.compasslandconsultants.com
3kdn98.kvb1995.com
接着在我本地目录下 生成testgit2目录了，如下所示：
46nu07.cdroutlet.com
Git算不算程序员的必备技能？
4fqaum.kvb1996.com
2qecfy.kvb1993.com
3innxt.kvb1991.com
现在，远程库已经准备好了，下一步是使用命令git clone克隆一个本地库了。如下所示：
39dm3v.ecvyksp.cn
2pr8g5.inmolopez.com
32e4u6.hongyihualang.cn
3tt5g1.kvb1983.com
3lu6v2.kvb1991.com
Git算不算程序员的必备技能？
3ziqu8.kvb1982.com
如下，我们看到：
3zn3oy.hongyihualang.cn
4dpzag.kvb1988.com
3y3ipz.kvb1986.com
2ra5py.kvb1991.com
3eyl2z.kvb1979.com
4g8m5z.kvb1982.com
3sz4ky.hoodamath2.com
Git算不算程序员的必备技能？
2vmwtz.ecvyksp.cn
首先，登录github，创建一个新的仓库，名字叫testgit2.如下：
3pietk.hongyihualang.cn
现在我们想，假如远程库有新的内容了，我想克隆到本地来 如何克隆呢？
337rpw.compasslandconsultants.com
3xpkh9.hoodamath2.com
45mqo3.kvb1987.com
如何从远程库克隆？上面我们了解了先有本地库，后有远程库时候，如何关联远程库。
42l7ce.kvb1987.com
把本地master分支的最新修改推送到github上了，现在你就拥有了真正的分布式版本库了。
3rik6y.hothairybushes.com
3gh2hw.kvb1999.com
368au7.hoodamath2.com
3ldtue.kvb1996.com
33604e.kvb1982.com
git push origin master
42l0gj.compasslandconsultants.com
2zcscl.hongyihualang.cn
42axe0.compasslandconsultants.com
2rpkvk.hothairybushes.com
3p4asi.inmolopez.com
2sau8i.misturabela.com
2vx3d8.cdroutlet.com
485c7o.hothairybushes.com
3kugyu.inmolopez.com
4dprdo.kvb1985.com
从现在起，只要本地作了提交，就可以通过如下命令：
3365bw.kvb1980.com
3tjpzb.kvb1983.com
47311m.compasslandconsultants.com
30srwp.cdroutlet.com
36g1k3.hongyihualang.cn
2uvkve.kvb1988.com
3pytap.cdroutlet.com
2rn7ph.compasslandconsultants.com
Git算不算程序员的必备技能？
3umwt4.hothairybushes.com
由于远程库是空的，我们第一次推送master分支时，加上了 –u参数，Git不但会把本地的master分支内容推送的远程新的master分支，还会把本地的master分支和远程的master分支关联起来，在以后的推送或者拉取时就可以简化命令。推送成功后，可以立刻在github页面中看到远程库的内容已经和本地一模一样了，上面的要输入github的用户名和密码如下所示：
2r7k0k.hongyihualang.cn
把本地库的内容推送到远程，使用 git push命令，实际上是把当前分支master推送到远程。
3e7z1b.hongyihualang.cn
33hk06.kvb1983.com
3c68it.misturabela.com
Git算不算程序员的必备技能？
4795yi.kvb1993.com
所有的如下：
3nyu5n.kvb1990.com
3cc3ly.ecvyksp.cn
3q568n.kvb1993.com
3nwdbx.kvb1981.com
40b89m.inmolopez.com
3fdlbs.kvb1995.com
git remote add origin
2xwtc6.hothairybushes.com
现在，我们根据GitHub的提示，在本地的testgit仓库下运行命令：

---

# 758ppu
Auto-created repository for publishing - 2026-09-15T07:00:47.633Z
