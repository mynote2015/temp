VMware-vSphere-VMhacking
===========================

VMware vSphere环境中的渗透测试


拥有VMware vSphere管理权限如何进一步向虚拟机渗透
-----------------

`拥有VMware vSphere管理权限如何进一步向虚拟机渗透`_

.. _拥有VMware vSphere管理权限如何进一步向虚拟机渗透: https://xz.aliyun.com/t/2817


VMware虚拟机中Windows/Linux系统用户密码的清除方法
-----------------

`VMware虚拟机中Windows/Linux系统用户密码的清除方法`_

.. _VMware虚拟机中Windows/Linux系统用户密码的清除方法: https://blog.csdn.net/my_xxh/article/details/82501780


Copying files from a virtual machine guest operating system that does not have network connectivity (2036993)
-----------------

`Copying files from a virtual machine guest operating system that does not have network connectivity (2036993)`_

.. _Copying files from a virtual machine guest operating system that does not have network connectivity (2036993): https://kb.vmware.com/s/article/2036993


使用DiskInternals Linux Reader读取Windows上的Linux文件系统
-----------------

`使用DiskInternals Linux Reader读取Windows上的Linux文件系统`_

.. _使用DiskInternals Linux Reader读取Windows上的Linux文件系统: https://www.linuxidc.com/Linux/2018-12/155719.htm














Using Markdown with Sphinx
--------------------------

You can use Markdown and reStructuredText in the same Sphinx project.
We support this natively on Read the Docs, and you can do it locally:

.. prompt:: bash $

    pip install recommonmark

Then in your ``conf.py``:

.. code-block:: python

    from recommonmark.parser import CommonMarkParser

    source_parsers = {
        '.md': CommonMarkParser,
    }

    source_suffix = ['.rst', '.md']

.. warning:: Markdown doesn't support a lot of the features of Sphinx,
          like inline markup and directives. However, it works for
          basic prose content. reStructuredText is the preferred
          format for technical documentation, please read `this blog post`_
          for motivation.

.. _this blog post: http://ericholscher.com/blog/2016/mar/15/dont-use-markdown-for-technical-docs/


External resources
------------------

Here are some external resources to help you learn more about Sphinx.

* `Sphinx documentation`_
* `RestructuredText primer`_
* `An introduction to Sphinx and Read the Docs for technical writers`_

.. _Sphinx documentation: http://www.sphinx-doc.org/
.. _RestructuredText primer: http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html
.. _An introduction to Sphinx and Read the Docs for technical writers: http://ericholscher.com/blog/2016/jul/1/sphinx-and-rtd-for-writers/
