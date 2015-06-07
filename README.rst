pkg-yaul-defaults
=================

Package default versions of yaul_ library for Debian releases.

Creating package
----------------

Replace ``stretch`` with your Debian's release codename

.. code:: shell

  git checkout debian/stretch
  debian/rules clean
  fakeroot debian/rules binary
  debian/rules clean

.. _yaul: https://github.com/ptomulik/yaul
